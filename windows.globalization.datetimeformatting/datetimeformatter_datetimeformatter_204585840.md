---
-api-id: M:Windows.Globalization.DateTimeFormatting.DateTimeFormatter.#ctor(System.String,Windows.Foundation.Collections.IIterable{System.String})
-api-type: winrt method
---

<!-- Method syntax
public DateTimeFormatter(System.String formatTemplate, Windows.Foundation.Collections.IIterable<System.String> languages)
-->

# Windows.Globalization.DateTimeFormatting.DateTimeFormatter.DateTimeFormatter

## -description
Creates a [DateTimeFormatter](datetimeformatter.md) object that is initialized by a format template string and language list.

## -parameters
### -param formatTemplate
A format template string that specifies the requested components. The order of the components is irrelevant. This can also be a format pattern. See the remarks for the [DateTimeFormatter](datetimeformatter.md) class for a list of valid format templates and format patterns.

### -param languages
The list of language identifiers, in priority order, that represent the choice of languages. These identifiers are used for resolving the template to a pattern and for formatting. See Remarks.

## -remarks
If your app passes language tags used in this class to any [National Language Support](https://msdn.microsoft.com/library/7a548074-0782-45e1-8051-80c3b9d81885) functions, it must first convert the tags by calling [ResolveLocaleName](https://msdn.microsoft.com/library/99264b22-3fb5-47e2-b0b9-42a6768e67c1).

**Starting in :** Language tags support the Unicode extensions "ca-" and "nu-". (See [Unicode Key/Type Definitions](https://go.microsoft.com/fwlink/p/?LinkId=308919).) Note that the "ca-" extension can affect the calendar used by [DateTimeFormatter](datetimeformatter.md) objects.

## -examples

## -see-also
[DateTimeFormatter(String)](datetimeformatter_datetimeformatter_290278668.md), [DateTimeFormatter(String, IIterable(String), String, String, String)](datetimeformatter_datetimeformatter_1042679024.md), [DateTimeFormatter(YearFormat, MonthFormat, DayFormat, DayOfWeekFormat)](datetimeformatter_datetimeformatter_242098968.md), [DateTimeFormatter(HourFormat, MinuteFormat, SecondFormat)](datetimeformatter_datetimeformatter_884240580.md), [DateTimeFormatter(YearFormat, MonthFormat, DayFormat, DayOfWeekFormat, HourFormat, MinuteFormat, SecondFormat, IIterable(String))](datetimeformatter_datetimeformatter_1763707544.md), [DateTimeFormatter(YearFormat, MonthFormat, DayFormat, DayOfWeekFormat, HourFormat, MinuteFormat, SecondFormat, IIterable(String), String, String, String)](datetimeformatter_datetimeformatter_321918312.md), [Date and time formatting sample](https://go.microsoft.com/fwlink/p/?LinkId=231618), [Unicode Key/Type Definitions](https://go.microsoft.com/fwlink/p/?LinkId=308919)

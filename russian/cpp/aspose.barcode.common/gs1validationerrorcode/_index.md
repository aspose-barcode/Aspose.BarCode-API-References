---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Идентифицирует ошибку проверки строки элемента GS1, URI Digital Link или значения в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Определяет ошибку проверки строки элемента GS1, URI Digital Link или значения.

```cpp
enum class GS1ValidationErrorCode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| EmptyElementString | 0 | Предоставленная строка элемента GS1 пуста. |
| MissingOpeningParenthesis | 1 | Отсутствует открывающая скобка, которая должна начинать идентификатор приложения. |
| MissingClosingParenthesis | 2 | У идентификатора приложения отсутствует закрывающая скобка. |
| InvalidApplicationIdentifier | 3 | Идентификатор приложения не содержит от двух до четырёх ASCII-цифр. |
| UnknownApplicationIdentifier | 4 | Предоставленный идентификатор приложения не определён поддерживаемым словарём синтаксиса GS1. |
| MissingValue | 5 | Идентификатор приложения присутствует без значения. |
| InvalidEscapeSequence | 6 | Значение содержит неподдерживаемую escape‑последовательность. Поддерживается только (. |
| ValueTooShort | 7 | Значение короче минимальной длины, определённой для его идентификатора приложения. |
| ValueTooLong | 8 | Значение длиннее максимальной длины, определённой для его Application Identifier. |
| InvalidCharacter | 9 | Значение содержит символ, не входящий в набор символов, разрешённый для его компонента. |
| InvalidChecksum | 10 | Числовая или буквенная контрольная сумма недействительна. |
| InvalidDate | 11 | Компонент даты не представляет собой осмысленную дату согласно правилам, определённым для его Application Identifier. |
| InvalidTime | 12 | Компонент времени находится за пределами разрешённого диапазона или имеет недопустимую структуру. |
| InvalidCodeListValue | 13 | Значение компонента отсутствует в разрешённом закрытом списке кодов. |
| InvalidComponentLength | 14 | Компонент не соответствует своей специфической структуре длины. |
| TruncatedComponent | 15 | Компонент фиксированной длины заканчивается до того, как присутствуют все необходимые символы. |
| UnexpectedData | 16 | Данные остаются после того, как все компоненты, определённые для Application Identifier, были использованы. |
| InvalidValue | 17 | Компонент нарушает правило содержимого, для которого нет более конкретного кода ошибки проверки. |
| GcpPrefixTooShort | 18 | Компонент слишком короткий, чтобы содержать минимальный четырёхзначный структурный префикс компании GS1. |
| InvalidGcpPrefix | 19 | Структурный префикс компании GS1 содержит символ, не являющийся ASCII-цифрой. |
| InvalidDigitalLinkUri | 20 | Предоставленное значение не является корректным абсолютным URI GS1 Digital Link. |
| UnsupportedDigitalLinkScheme | 21 | URI GS1 Digital Link использует схему, отличную от HTTP или HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | Путь URI GS1 Digital Link не содержит поддерживаемый первичный ключ. |
| InvalidDigitalLinkPath | 23 | Путь URI GS1 Digital Link не состоит из корректных пар AI и значений. |
| InvalidDigitalLinkQualifier | 24 | Идентификатор приложения в пути не является разрешённым квалификатором в данной позиции. |
| InvalidDigitalLinkQueryParameter | 25 | Параметр запроса GS1 Digital Link сформирован неверно. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Идентификатор приложения не допускается в качестве атрибута данных GS1 Digital Link. |
| InvalidPercentEncoding | 27 | Компонент URI GS1 Digital Link содержит некорректное процентное кодирование. |
| MultipleDigitalLinkPrimaryKeys | 28 | Более одного элемента может быть выбрано в качестве первичного ключа GS1 Digital Link. |
| UnsupportedElementCombination | 29 | Предоставленная комбинация элементов GS1 не поддерживается выбранной символогией или режимом кодирования. |

## См. также

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

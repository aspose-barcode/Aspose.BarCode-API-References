---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes for Python via .NET API Reference"
description: 
type: docs
url: /ru/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Определяет ошибку проверки строки элемента GS1, URI Digital Link или значения.

## Members
| Имя члена | Описание |
| :- | :- |
| EMPTY_ELEMENT_STRING | Предоставленная строка элемента GS1 пуста. |
| MISSING_OPENING_PARENTHESIS | Отсутствует открывающая скобка, которая должна начинать идентификатор приложения. |
| MISSING_CLOSING_PARENTHESIS | У идентификатора приложения нет закрывающей скобки. |
| INVALID_APPLICATION_IDENTIFIER | Идентификатор приложения не содержит от двух до четырёх ASCII-цифр. |
| UNKNOWN_APPLICATION_IDENTIFIER | Предоставленный идентификатор приложения не определён поддерживаемым словарём синтаксиса GS1. |
| MISSING_VALUE | Идентификатор приложения присутствует без значения. |
| INVALID_ESCAPE_SEQUENCE | Значение содержит неподдерживаемую управляющую последовательность. Поддерживается только \(. |
| VALUE_TOO_SHORT | Значение короче минимальной длины, определённой для его идентификатора приложения. |
| VALUE_TOO_LONG | Значение длиннее максимальной длины, определённой для его идентификатора приложения. |
| INVALID_CHARACTER | Значение содержит символ, не входящий в набор символов, разрешённый для его компонента. |
| INVALID_CHECKSUM | Числовая или буквенная контрольная сумма недействительна. |
| INVALID_DATE | Компонент даты не является осмысленной датой согласно правилам, определённым для его идентификатора приложения. |
| INVALID_TIME | Временной компонент находится за пределами разрешённого диапазона или имеет недопустимую структуру. |
| INVALID_CODE_LIST_VALUE | Значение компонента отсутствует в разрешённом закрытом списке кодов. |
| INVALID_COMPONENT_LENGTH | Компонент не соответствует своей специфической по длине структуре. |
| TRUNCATED_COMPONENT | Компонент фиксированной длины заканчивается до того, как присутствуют все требуемые символы. |
| UNEXPECTED_DATA | Данные остаются после того, как все компоненты, определённые для идентификатора приложения, были обработаны. |
| INVALID_VALUE | Компонент нарушает правило содержимого, для которого нет более конкретного кода ошибки проверки. |
| GCP_PREFIX_TOO_SHORT | Компонент слишком короткий, чтобы содержать минимум четырёхзначный структурный префикс компании GS1. |
| INVALID_GCP_PREFIX | Структурный префикс компании GS1 содержит символ, отличный от ASCII-цифры. |
| INVALID_DIGITAL_LINK_URI | Предоставленное значение не является корректным абсолютным URI GS1 Digital Link. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | URI GS1 Digital Link использует схему, отличную от HTTP или HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Путь URI GS1 Digital Link не содержит поддерживаемый первичный ключ. |
| INVALID_DIGITAL_LINK_PATH | Путь URI GS1 Digital Link не состоит из корректных пар AI и значения. |
| INVALID_DIGITAL_LINK_QUALIFIER | Идентификатор приложения в пути не является разрешённым квалификатором в данной позиции. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Параметр запроса GS1 Digital Link имеет неверный формат. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Идентификатор Application Identifier не допускается в качестве атрибута данных GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Компонент URI GS1 Digital Link содержит некорректное процентное кодирование. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Более одного элемента может быть выбрано в качестве первичного ключа GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | Предоставленная комбинация элементов GS1 не поддерживается выбранной символьной системой или режимом кодирования. |

### See Also

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)


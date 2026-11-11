---
title: "Перечисление GS1ValidationErrorCode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Common.GS1ValidationErrorCode. Определяет ошибку проверки строки элемента GS1, URI Digital Link или значения"
type: docs
weight: 430
url: /ru/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Определяет ошибку проверки строки элемента GS1, URI Digital Link или значения.

```csharp
public enum GS1ValidationErrorCode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| EmptyElementString | `0` | Предоставленная строка элемента GS1 пуста. |
| MissingOpeningParenthesis | `1` | Отсутствует открывающая скобка, которая должна начинать идентификатор приложения. |
| MissingClosingParenthesis | `2` | У идентификатора приложения нет закрывающей скобки. |
| InvalidApplicationIdentifier | `3` | Идентификатор приложения не содержит от двух до четырёх ASCII-цифр. |
| UnknownApplicationIdentifier | `4` | Предоставленный идентификатор приложения не определён поддерживаемым словарём синтаксиса GS1. |
| MissingValue | `5` | Идентификатор приложения присутствует без значения. |
| InvalidEscapeSequence | `6` | Значение содержит неподдерживаемую escape‑последовательность. Поддерживается только \\( |
| ValueTooShort | `7` | Значение короче минимальной длины, определённой для его идентификатора приложения. |
| ValueTooLong | `8` | Значение длиннее максимальной длины, определённой для его идентификатора приложения. |
| InvalidCharacter | `9` | Значение содержит символ, не входящий в набор символов, разрешённый для его компонента. |
| InvalidChecksum | `10` | Числовая или буквенная контрольная сумма недействительна. |
| InvalidDate | `11` | Компонент даты не является осмысленной датой согласно правилам, определённым для его идентификатора приложения. |
| InvalidTime | `12` | Компонент времени выходит за пределы разрешённого диапазона или имеет недопустимую структуру. |
| InvalidCodeListValue | `13` | Значение компонента отсутствует в разрешённом закрытом списке кодов. |
| InvalidComponentLength | `14` | Компонент не соответствует своей специфической по длине структуре. |
| TruncatedComponent | `15` | Компонент фиксированной длины заканчивается до того, как присутствуют все требуемые символы. |
| UnexpectedData | `16` | Данные остаются после того, как все компоненты, определённые для идентификатора приложения, были обработаны. |
| InvalidValue | `17` | Компонент нарушает правило содержимого, для которого нет более конкретного кода ошибки проверки. |
| GcpPrefixTooShort | `18` | Компонент слишком короток, чтобы содержать минимальный четырёхзначный структурный префикс компании GS1. |
| InvalidGcpPrefix | `19` | Структурный префикс компании GS1 содержит символ, отличный от ASCII-цифры. |
| InvalidDigitalLinkUri | `20` | Предоставленное значение не является корректным абсолютным URI GS1 Digital Link. |
| UnsupportedDigitalLinkScheme | `21` | URI GS1 Digital Link использует схему, отличную от HTTP или HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | Путь URI GS1 Digital Link не содержит поддерживаемый первичный ключ. |
| InvalidDigitalLinkPath | `23` | Путь URI GS1 Digital Link не состоит из корректных пар AI и значения. |
| InvalidDigitalLinkQualifier | `24` | Идентификатор приложения в пути не допускается в этой позиции. |
| InvalidDigitalLinkQueryParameter | `25` | Параметр запроса GS1 Digital Link сформирован неверно. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Идентификатор приложения не допускается в качестве атрибута данных GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Компонент URI GS1 Digital Link содержит некорректное процентное кодирование. |
| MultipleDigitalLinkPrimaryKeys | `28` | Более одного элемента может быть выбрано в качестве первичного ключа GS1 Digital Link. |
| UnsupportedElementCombination | `29` | Предоставленная комбинация элементов GS1 не поддерживается выбранной символьной системой или режимом кодирования. |

### См. также

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



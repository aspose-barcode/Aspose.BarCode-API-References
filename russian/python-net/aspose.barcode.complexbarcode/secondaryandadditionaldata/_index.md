---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Класс для хранения вторичных и дополнительных данных HIBC LIC.

Тип SecondaryAndAdditionalData раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| SecondaryAndAdditionalData() | Инициализирует новый экземпляр класса SecondaryAndAdditionalData |
## Properties
| Name | Описание |
| :- | :- |
| expiry_date_format | Определяет формат даты истечения срока. |
| expiry_date | Определяет дату истечения срока. Будет использоваться, если ExpiryDateFormat не установлен в None. |
| lot_number | Определяет номер партии или лота. Номер партии/лота должен быть буквенно-цифровой строкой длиной до 18 символов. . |
| serial_number | Определяет серийный номер. Серийный номер должен быть буквенно-цифровой строкой длиной до 18 символов. |
| date_of_manufacture | Определяет дату производства.<br/>            Дату производства можно установить в DateTime.MinValue, чтобы не использовать это поле.<br/>            Значение по умолчанию: DateTime.MinValue |
| quantity | Определяет количество, должно быть целым числом от 0 до 500. <br/>            Количество можно установить в -1, чтобы не использовать это поле.<br/>            Значение по умолчанию: -1 |
## Methods
| Name | Описание |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Создаёт вторичные и дополнительные вспомогательные данные из строкового формата в соответствии со спецификацией HIBC LIC. |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


---
title: "DotCodeParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/dotcodeparameters/
---

## DotCodeParameters class

Параметры DotCode.

Тип DotCodeParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| aspect_ratio | Соотношение высоты к ширине модуля 2D BarCode. |
| encode_mode | Определяет режим кодирования DotCode. <br/>            Значение по умолчанию: Auto. |
| is_reader_initialization | Указывает, используется ли код для инструкций считывателя, чтобы интерпретировать последующие данные как команды инициализации или перепрограммирования считывателя штрихкода.<br/>            Значение по умолчанию — false. |
| structured_append_mode_barcode_id | Определяет ID штрих‑кода режима структурированного добавления DotCode. ID начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — -1. |
| structured_append_mode_barcodes_count | Определяет количество штрих‑кодов режима структурированного добавления DotCode. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. |
| eci_encoding | Определяет кодировку ECI. Используется, когда DotCodeEncodeMode установлен в Auto.<br/>            Значение по умолчанию: ISO-8859-1 |
| rows | Определяет количество строк. Сумма количества строк и столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5.<br/>            Значение по умолчанию: -1 |
| columns | Определяет количество столбцов. Сумма количества строк и столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5.<br/>            Значение по умолчанию: -1 |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


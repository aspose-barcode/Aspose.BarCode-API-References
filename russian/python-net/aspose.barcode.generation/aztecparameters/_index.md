---
title: "AztecParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Параметры Aztec.

Тип AztecParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| encode_mode | Получает или задает режим кодирования Aztec. <br/>            Значение по умолчанию: Auto. |
| eci_encoding | Получает или задает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto.<br/>            Значение по умолчанию: ISO-8859-1 |
| structured_append_barcode_id | Идентификатор штрихкода для режима Structured Append штрихкода Aztec. Идентификатор штрихкода должен находиться в диапазоне от 1 до количества штрихкодов.<br/>            Значение по умолчанию: 0 |
| structured_append_barcodes_count | Количество штрихкодов для режима Structured Append штрихкода Aztec. Количество штрихкодов должно быть в диапазоне от 1 до 26.<br/>            Значение по умолчанию: 0 |
| structured_append_file_id | Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы.<br/>            Значение по умолчанию: пустая строка |
| error_level | Уровень коррекции ошибок для штрихкодов типа Aztec.<br/>            Значение должно быть от 5 до 95. |
| symbol_mode | Получает или задает режим символа Aztec.<br/>            Значение по умолчанию: AztecSymbolMode.Auto. |
| layers_count | Получает или задает количество слоёв символа Aztec. Количество слоёв должно быть в диапазоне от 1 до 3 для компактного режима и<br/>            в диапазоне от 1 до 32 для полного диапазона.<br/>            Значение по умолчанию: 0 (авто). |
| is_reader_initialization | Используется для указания считывателю интерпретировать данные, содержащиеся в символе<br/>            как программирование для инициализации считывателя. |
| aspect_ratio | Соотношение высоты к ширине модуля 2D BarCode. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


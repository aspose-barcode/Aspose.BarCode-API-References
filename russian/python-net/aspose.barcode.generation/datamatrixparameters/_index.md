---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Параметры DataMatrix.

Тип DataMatrixParameters раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| ecc_type | Получает или задает тип ECC Datamatrix.<br/>            Значение по умолчанию: DataMatrixEccType.Ecc200. |
| version | Получает или задает размер символа Datamatrix.<br/>            Значение по умолчанию: Version.Auto. |
| encode_mode | Режим кодирования штрих‑кода Datamatrix.<br/>            Значение по умолчанию: EncodeMode.Auto. |
| structured_append_barcode_id | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Datamatrix.<br/>            Значение по умолчанию: 0 |
| structured_append_barcodes_count | Количество штрих‑кодов для режима Structured Append штрих‑кода Datamatrix.<br/>            Значение по умолчанию: 0 |
| structured_append_file_id | Идентификатор файла для режима Structured Append штрих‑кода Datamatrix.<br/>            Значение по умолчанию: 0 |
| is_reader_programming | Используется для указания считывателю интерпретировать данные, содержащиеся в символе<br/>            как программирование для инициализации считывателя.<br/>            Значение по умолчанию: false |
| macro_characters | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах.<br/>            Может использоваться только с DataMatrixEccType.Ecc200 или DataMatrixEccType.EccAuto.<br/>            Не может использоваться с EncodeTypes.GS1DataMatrix<br/>            Значение по умолчанию: MacroCharacters.None. |
| aspect_ratio | Соотношение высоты к ширине модуля 2D BarCode. |
| eci_encoding | Получает или задает кодировку ECI. Используется, когда EncodeMode установлен в Auto.<br/>            Значение по умолчанию: ISO-8859-1 |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


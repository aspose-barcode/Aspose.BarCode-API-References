---
title: "Aspose::BarCode::Generation::DotCodeParameters класс"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::DotCodeParameters класс. Параметры DotCode в C++."
type: docs
weight: 2200
url: /ru/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


Параметры DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_Columns](./get_columns/)() const | Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Определяет кодировку ECI. Используется, когда DotCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false. |
| [get_Rows](./get_rows/)() const | Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Определяет ID штрих‑кода в режиме структурированного добавления DotCode. ID начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию: -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Определяет количество штрих‑кодов в режиме структурированного добавления DotCode. Значение по умолчанию: -1. Количество должно быть в диапазоне от 1 до 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_Columns](./set_columns/)(int32_t) | Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Определяет кодировку ECI. Используется, когда DotCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрихкодов. Значение по умолчанию — false. |
| [set_Rows](./set_rows/)(int32_t) | Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Определяет ID штрих‑кода в режиме структурированного добавления DotCode. ID начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию: -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Определяет количество штрих‑кодов в режиме структурированного добавления DotCode. Значение по умолчанию: -1. Количество должно быть в диапазоне от 1 до 35. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [DotCodeParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

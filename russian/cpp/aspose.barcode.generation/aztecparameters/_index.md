---
title: "Класс Aspose::BarCode::Generation::AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::Generation::AztecParameters. Параметры Aztec в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Параметры Aztec.

```cpp
class AztecParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Получает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1. |
| [get_EncodeMode](./get_encodemode/)() const | Получает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Уровень коррекции ошибок типов штрих‑кода Aztec. Значение должно быть от 5 до 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [get_LayersCount](./get_layerscount/)() const | Получает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для компактного режима и от 1 до 32 для режима полного диапазона. Значение по умолчанию: 0 (авто). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен находиться в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка |
| [get_SymbolMode](./get_symbolmode/)() const | Получает режим символа Aztec. Значение по умолчанию: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Устанавливает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Уровень коррекции ошибок типов штрих‑кода Aztec. Значение должно быть от 5 до 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Устанавливает количество слоёв символа Aztec. Количество слоёв должно находиться в диапазоне от 1 до 3 для компактного режима и от 1 до 32 для режима полного диапазона. Значение по умолчанию: 0 (авто). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Aztec. Идентификатор штрих‑кода должен находиться в диапазоне от 1 до количества штрих‑кодов. Значение по умолчанию: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Количество штрих‑кодов для режима Structured Append штрих‑кода Aztec. Количество штрих‑кодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Идентификатор файла для режима Structured Append штрих‑кода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Устанавливает режим символа Aztec. Значение по умолчанию: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [AztecParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

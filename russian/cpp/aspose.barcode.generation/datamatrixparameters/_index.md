---
title: "Класс Aspose::BarCode::Generation::DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::Generation::DataMatrixParameters. Параметры DataMatrix в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Параметры DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_EccType](./get_ecctype/)() const | Получает тип ECC для Datamatrix. Значение по умолчанию: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Получает кодировку ECI. Используется, когда EncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу инициализации считывателя. Значение по умолчанию: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с [DataMatrixEccType.Ecc200](../datamatrixecctype/) или [DataMatrixEccType.EccAuto](../datamatrixecctype/). Нельзя использовать с [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Значение по умолчанию: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Количество штрих‑кодов для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Идентификатор файла для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [get_Version](./get_version/)() const | Получает размер символа Datamatrix. Значение по умолчанию: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Устанавливает тип ECC Datamatrix. Значение по умолчанию: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Устанавливает кодировку ECI. Используется, когда EncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Режим кодирования штрих‑кода Datamatrix. Значение по умолчанию: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу инициализации считывателя. Значение по умолчанию: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Значения Macro Characters 05 и 06 используются для получения более компактного кодирования в специальных режимах. Можно использовать только с [DataMatrixEccType.Ecc200](../datamatrixecctype/) или [DataMatrixEccType.EccAuto](../datamatrixecctype/). Нельзя использовать с [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Значение по умолчанию: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Идентификатор штрих‑кода для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Количество штрих‑кодов для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Идентификатор файла для режима Structured Append штрих‑кода Datamatrix. Значение по умолчанию: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Устанавливает размер символа Datamatrix. Значение по умолчанию: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [DataMatrixParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

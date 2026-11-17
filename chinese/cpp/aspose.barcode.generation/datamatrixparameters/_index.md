---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::DataMatrixParameters 类。C++ 中的 DataMatrix 参数。"
type: docs
weight: 2000
url: /zh/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix 参数。

```cpp
class DataMatrixParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [get_EccType](./get_ecctype/)() const | 获取 DataMatrix ECC 类型。默认值: [DataMatrixEccType.Ecc200](../datamatrixecctype/)。 |
| [get_ECIEncoding](./get_eciencoding/)() const | 获取 ECI 编码。当 EncodeMode 为 Auto 时使用。默认值: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | DataMatrix 条码的编码模式。默认值: [EncodeMode.Auto](../aztecencodemode/)。 |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | 用于指示阅读器将符号中包含的数据解释为阅读器初始化的编程。默认值: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 [DataMatrixEccType.Ecc200](../datamatrixecctype/) 或 [DataMatrixEccType.EccAuto](../datamatrixecctype/) 一起使用。不能与 [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) 一起使用。默认值: [MacroCharacters.None](../barcodeclassifications/)。 |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | DataMatrix 条码结构化追加模式的条码 ID。默认值: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | DataMatrix 条码结构化追加模式的条码计数。默认值: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datamatrix 条形码的结构追加模式的文件 ID。默认值：0 |
| [get_Version](./get_version/)() const | 获取 Datamatrix 符号大小。默认值：[Version.Auto](../aztecencodemode/)。 |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 模块的高/宽比。 |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | 设置 Datamatrix ECC 类型。默认值：[DataMatrixEccType.Ecc200](../datamatrixecctype/)。 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | 设置 ECI 编码。当 EncodeMode 为 Auto 时使用。默认值：ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | DataMatrix 条码的编码模式。默认值: [EncodeMode.Auto](../aztecencodemode/)。 |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | 用于指示阅读器将符号中包含的数据解释为阅读器初始化的编程。默认值: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | 宏字符 05 和 06 的值用于在特殊模式下获得更紧凑的编码。只能与 [DataMatrixEccType.Ecc200](../datamatrixecctype/) 或 [DataMatrixEccType.EccAuto](../datamatrixecctype/) 一起使用。不能与 [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) 一起使用。默认值: [MacroCharacters.None](../barcodeclassifications/)。 |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | DataMatrix 条码结构化追加模式的条码 ID。默认值: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | DataMatrix 条码结构化追加模式的条码计数。默认值: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datamatrix 条形码的结构追加模式的文件 ID。默认值：0 |
| [set_Version](./set_version/)(DataMatrixVersion) | 设置 Datamatrix 符号大小。默认值：[Version.Auto](../aztecencodemode/)。 |
| [ToString](./tostring/)() const override | 返回此 [DataMatrixParameters](./) 的可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

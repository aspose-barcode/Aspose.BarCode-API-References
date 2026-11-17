---
title: "Aspose::BarCode::Generation::BarcodeGenerator 类"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::BarcodeGenerator 类。BarcodeGenerator 用于在 C++ 中生成后端条形码图像。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | 创建 [BarcodeGenerator](./) 的实例。 |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | 创建 [BarcodeGenerator](./) 的实例。 |
| [Dispose](./dispose/)() override | 清理正在使用的任何资源。 |
| [ExportToXml](./exporttoxml/)(System::String) | 将 [BarCode](../../aspose.barcode/) 属性导出到指定的 xml 文件 |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | 将 [BarCode](../../aspose.barcode/) 属性导出到指定的 xml 流 |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 在当前设置下生成条形码图像。 |
| [get_BarcodeType](./get_barcodetype/)() | 条形码符号类型。 |
| [get_CodeText](./get_codetext/)() | 要编码的文本。 |
| [get_Parameters](./get_parameters/)() const | [Generation](../) 参数。 |
| static [ImportFromXml](./importfromxml/)(System::String) | 从指定的 xml 文件导入 [BarCode](../../aspose.barcode/) 属性并创建 [BarcodeGenerator](./) 实例。 |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 从指定的 xml 流导入 [BarCode](../../aspose.barcode/) 属性并创建 [BarcodeGenerator](./) 实例。 |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | 将条形码图像以特定格式保存到流中。 |
| [Save](./save/)(System::String, BarCodeImageFormat) | 将条形码图像以特定格式保存到指定文件中。 |
| [Save](./save/)(System::String) | 将条形码图像保存到指定文件。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | 条形码符号类型。 |
| [set_CodeText](./set_codetext/)(System::String) | 要编码的文本。 |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | 将 codetext 设置为字节序列。 |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## 备注


支持的符号类型：1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

此示例展示了如何创建并保存条形码图像。
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

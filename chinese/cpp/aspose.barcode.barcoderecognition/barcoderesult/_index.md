---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult 类"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult 类。存储已识别的条形码数据，如 SingleDecodeType 类型、System::String codetext、BarCodeRegionParameters 区域以及其他参数（C++）。"
type: docs
weight: 700
url: /zh/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


存储已识别的条形码数据，如 [SingleDecodeType](../singledecodetype/) 类型、**System::String** codetext、[BarCodeRegionParameters](../barcoderegionparameters/) 区域以及其他参数

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | 创建 [BarCodeResult](./) 类的副本。 |
| [Clone](./clone/)() override | 创建 [BarCodeResult](./) 类的副本。 |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | 返回一个值，指示此实例是否等于指定的 [BarCodeResult](./) 值。 |
| [get_CodeBytes](./get_codebytes/)() const | 获取已编码的代码字节 |
| [get_CodeText](./get_codetext/)() const | 获取代码文本 |
| [get_CodeType](./get_codetype/)() const | 获取条形码类型 |
| [get_CodeTypeName](./get_codetypename/)() | 获取条形码类型的名称 |
| [get_Confidence](./get_confidence/)() const | 获取已识别条形码的识别置信度水平 |
| [get_Extended](./get_extended/)() const | 获取已识别条形码的扩展参数 |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | 获取已识别条形码的 ISO/IEC 符号质量评估结果。 |
| [get_ReadingQuality](./get_readingquality/)() const | 获取读取质量。适用于 1D 和邮政条形码。 |
| [get_Region](./get_region/)() const | 获取条形码区域 |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | 获取带编码的代码文本。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [BarCodeResult](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取 [BarCodeResult](./)。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

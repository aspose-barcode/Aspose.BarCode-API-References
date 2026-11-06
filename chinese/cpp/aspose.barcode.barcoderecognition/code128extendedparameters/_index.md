---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters 类。存储在 C++ 中识别的 Code128 条码的特殊数据。"
type: docs
weight: 1300
url: /zh/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


存储已识别的 Code128 条码的特殊数据。

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | 获取已识别的 Code128 条码的 [Code128DataPortion](../code128dataportion/) 数组 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [Code128ExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


表示已识别条码的区域和条码角度

此示例展示如何获取 code128 原始值
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

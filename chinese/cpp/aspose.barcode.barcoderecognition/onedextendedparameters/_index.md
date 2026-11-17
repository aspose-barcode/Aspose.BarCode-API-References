---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters 类"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters 类。存储已识别的一维条码的特殊数据，例如在 C++ 中的独立代码文本和校验和。"
type: docs
weight: 2700
url: /zh/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


存储已识别 1D 条码的特殊数据，例如独立的代码文本和校验和

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | 获取一维条码的校验和。 |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 是否所有参数仅具有默认值 |
| [get_Value](./get_value/)() const | 获取一维条码的代码文本（不含校验和）。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [OneDExtendedParameters](./) 的人类可读字符串表示。 |
## 备注


此示例展示如何获取一维条码的值和校验和。
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## 另见

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

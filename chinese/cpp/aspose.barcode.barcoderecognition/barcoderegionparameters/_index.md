---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters 类。表示在 C++ 中识别的条码的区域和条码角度。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


表示已识别条码的区域和条码角度

```cpp
class BarCodeRegionParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Angle](./get_angle/)() const | 获取条码的角度（0-360）。 |
| [get_Points](./get_points/)() const | 获取 [Point](../)s 数组，界定条码区域 |
| [get_Quadrangle](./get_quadrangle/)() const | 获取 [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) 界定的条码区域 |
| [get_Rectangle](./get_rectangle/)() const | 获取 **System::Drawing::Rectangle** 界定的条码区域 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [ToString](./tostring/)() const override | 返回此 [BarCodeRegionParameters](./) 的可读字符串表示。 |
## 备注


此示例展示了如何获取条码角度和界定的四边形值
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
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

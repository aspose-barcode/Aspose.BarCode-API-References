---
title: "فئة Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters. تمثّل منطقة الباركود المُعترف به وزاوية الباركود في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


يمثل منطقة الباركود المُعترف به وزاوية الباركود

```cpp
class BarCodeRegionParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Angle](./get_angle/)() const | يحصل على زاوية الباركود (0-360). |
| [get_Points](./get_points/)() const | يحصل على مصفوفة [Point](../) التي تحدد منطقة الباركود |
| [get_Quadrangle](./get_quadrangle/)() const | يحصل على [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) التي تحدد منطقة الباركود |
| [get_Rectangle](./get_rectangle/)() const | يحصل على **System::Drawing::Rectangle** التي تحدد منطقة الباركود |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيل نصي قابل للقراءة للإنسان لهذا [BarCodeRegionParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على زاوية الباركود وقيم المربع المحدد للمنطقة
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

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

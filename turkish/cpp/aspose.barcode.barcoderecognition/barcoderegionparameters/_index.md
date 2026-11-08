---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters sınıfı. C++'da tanınan barkodun bölgesini ve barkod açısını temsil eder."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


Tanınan barkodun bölgesini ve barkod açısını temsil eder

```cpp
class BarCodeRegionParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Angle](./get_angle/)() const | Barkodun açısını (0-360) alır. |
| [get_Points](./get_points/)() const | [Point](../) dizisini alır, barkod bölgesini sınırlayan. |
| [get_Quadrangle](./get_quadrangle/)() const | [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) ile barkod bölgesini sınırlayan değerleri alır. |
| [get_Rectangle](./get_rectangle/)() const | **System::Drawing::Rectangle** ile barkod bölgesini sınırlayan değerleri alır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [BarCodeRegionParameters](./) öğesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnek, barkod açısını ve sınırlayıcı dörtgen değerlerini nasıl alacağınızı gösterir.
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

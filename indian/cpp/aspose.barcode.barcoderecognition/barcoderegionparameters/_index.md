---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeRegionParameters class। पहचाने गए बारकोड के क्षेत्र और बारकोड कोण को C++ में दर्शाता है।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class


पहचाने गए बारकोड का क्षेत्र और बारकोड कोण दर्शाता है।

```cpp
class BarCodeRegionParameters : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Angle](./get_angle/)() const | बारकोड का कोण प्राप्त करता है (0-360)। |
| [get_Points](./get_points/)() const | बारकोड क्षेत्र को सीमित करने वाले [Point](../)s एरे को प्राप्त करता है। |
| [get_Quadrangle](./get_quadrangle/)() const | बारकोड क्षेत्र को सीमित करने वाले [Aspose::BarCode::BarCodeRecognition::Quadrangle](../quadrangle/) को प्राप्त करता है। |
| [get_Rectangle](./get_rectangle/)() const | बारकोड क्षेत्र को सीमित करने वाले **System::Drawing::Rectangle** को प्राप्त करता है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [BarCodeRegionParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दर्शाता है कि बारकोड कोण और सीमित क्वाड्रैंगल मान कैसे प्राप्त करें।
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

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. C++ में पहचाने गए Code128 बारकोड का विशेष डेटा संग्रहीत करता है।"
type: docs
weight: 1300
url: /hi/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Code128 पहचाने गए बारकोड के विशेष डेटा को संग्रहीत करता है।

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | पहचाने गए Code128 बारकोड की [Code128DataPortion](../code128dataportion/) सरणी प्राप्त करता है |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [Code128ExtendedParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


पहचाने गए बारकोड का क्षेत्र और बारकोड कोण दर्शाता है।

यह उदाहरण दिखाता है कि code128 कच्चे मान कैसे प्राप्त करें
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

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

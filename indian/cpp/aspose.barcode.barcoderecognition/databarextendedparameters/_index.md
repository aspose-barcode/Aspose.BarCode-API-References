---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters क्लास। पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी को C++ में संग्रहीत करता है।"
type: docs
weight: 1400
url: /hi/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी को संग्रहीत करता है।

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | DataBar 2D सम्मिलित घटक फ़्लैग प्राप्त करता है। डिफ़ॉल्ट मान false है। |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [DataBarExtendedParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि DataBar अतिरिक्त जानकारी कैसे प्राप्त करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

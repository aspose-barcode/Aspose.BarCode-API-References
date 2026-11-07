---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult क्लास"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult क्लास। मान्यता प्राप्त बारकोड डेटा संग्रहीत करता है जैसे SingleDecodeType प्रकार, System::String codetext, BarCodeRegionParameters region और अन्य पैरामीटर C++ में।"
type: docs
weight: 700
url: /hi/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


मान्यता प्राप्त बारकोड डेटा संग्रहीत करता है जैसे [SingleDecodeType](../singledecodetype/) प्रकार, **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) region और अन्य पैरामीटर

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | एक प्रति बनाता है [BarCodeResult](./) क्लास की। |
| [Clone](./clone/)() override | एक प्रति बनाता है [BarCodeResult](./) क्लास की। |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BarCodeResult](./) मान के बराबर है या नहीं। |
| [get_CodeBytes](./get_codebytes/)() const | एन्कोडेड कोड बाइट्स प्राप्त करता है |
| [get_CodeText](./get_codetext/)() const | कोड टेक्स्ट प्राप्त करता है |
| [get_CodeType](./get_codetype/)() const | बारकोड प्रकार प्राप्त करता है |
| [get_CodeTypeName](./get_codetypename/)() | बारकोड प्रकार का नाम प्राप्त करता है |
| [get_Confidence](./get_confidence/)() const | मान्यता प्राप्त बारकोड का पहचान विश्वसनीयता स्तर प्राप्त करता है |
| [get_Extended](./get_extended/)() const | मान्यता प्राप्त बारकोड के विस्तारित पैरामीटर प्राप्त करता है |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | मान्यता प्राप्त बारकोड के लिए ISO/IEC प्रतीक गुणवत्ता मूल्यांकन परिणाम प्राप्त करता है। |
| [get_ReadingQuality](./get_readingquality/)() const | पढ़ने की गुणवत्ता प्राप्त करता है। 1D और डाक बारकोड के लिए काम करता है। |
| [get_Region](./get_region/)() const | बारकोड क्षेत्र प्राप्त करता है |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [BarCodeResult](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह नमूना दिखाता है कि [BarCodeResult](./) कैसे प्राप्त किया जाए।
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

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

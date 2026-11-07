---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters क्लास"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters क्लास। C++ में पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी संग्रहीत करता है।"
type: docs
weight: 2800
url: /hi/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


पहचाने गए बारकोड की MacroPdf417 मेटाडाटा जानकारी को संग्रहीत करता है।

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | फ़्लैग जो दर्शाता है कि MicroPdf417 बारकोड 908, 909, 910 या 911 कोड 128 अनुकरण कोडवर्ड्स के साथ एन्कोड किया गया है। |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [get_IsLinked](./get_islinked/)() const | फ़्लैग जो दर्शाता है कि बारकोड को 1D बारकोड से लिंक किया जाना चाहिए। |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि प्रतीक में निहित डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 प्राप्तकर्ता नाम (वैकल्पिक)। |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 चेकसम (वैकल्पिक)। |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | बारकोड का फ़ाइल आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 फ़ाइल नाम (वैकल्पिक)। |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 फ़ाइल आकार (वैकल्पिक)। |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | बारकोड का सेगमेंट आईडी प्राप्त करता है, केवल MacroPdf417 के साथ उपलब्ध। |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Macro PDF417 बारकोड सेगमेंट्स की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 प्रेषक नाम (वैकल्पिक)। |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | दर्शाता है कि सेगमेंट Macro PDF417 फ़ाइल का अंतिम सेगमेंट है या नहीं। |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 टाइम स्टैम्प (वैकल्पिक)। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [Pdf417ExtendedParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि Macro Pdf417 मेटाडाटा कैसे प्राप्त करें।
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

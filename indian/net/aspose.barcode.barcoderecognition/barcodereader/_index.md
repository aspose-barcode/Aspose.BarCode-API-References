---
title: "BarCodeReader क्लास"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeReader क्लास। BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं और फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है"
type: docs
weight: 70
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।

```csharp
public class BarCodeReader : Component
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | डिफ़ॉल्ट मानों के साथ `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। ReadBarCodes() मेथड को कॉल करने से पहले छवि सेट करना (SetBitmapImage()) आवश्यक है। |
| [BarCodeReader](barcodereader/#constructor_8)(Bitmap) | `BarCodeReader` क्लास का नया इंस्टेंस एक छवि से इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_1)(LuminanceFrame) | `BarCodeReader` क्लास का नया इंस्टेंस एक ल्यूमिनेंस फ्रेम से इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_15)(Stream) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_18)(string) | `BarCodeReader` क्लास का नया इंस्टेंस फ़ाइल से इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_9)(Bitmap, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_10)(Bitmap, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_2)(LuminanceFrame, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_3)(LuminanceFrame, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_16)(Stream, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_17)(Stream, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_19)(string, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_20)(string, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_11)(Bitmap, Rectangle, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_12)(Bitmap, Rectangle, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_13)(Bitmap, Rectangle[], BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_14)(Bitmap, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_4)(LuminanceFrame, Rectangle, BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_5)(LuminanceFrame, Rectangle, params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_6)(LuminanceFrame, Rectangle[], BaseDecodeType) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](barcodereader/#constructor_7)(LuminanceFrame, Rectangle[], params BaseDecodeType[]) | `BarCodeReader` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/) { get; set; } | मान्यता के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है या सेट करता है। [`ReadBarCodes`](./readbarcodes/) को कॉल करने से पहले इसे सेट करना आवश्यक है। |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | मुख्य BarCode डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं। |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | पहचाने गए [`BarCodeResult`](../barcoderesult/) का एरे प्राप्त करता है |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | पहचाने गए बारकोड की संख्या प्राप्त करता है |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings आपको मान्यता की गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है। |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | मिलीसेकंड में मान्यता प्रक्रिया का टाइमआउट प्राप्त करता है या सेट करता है। |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | प्रोसेसर कोर उपयोग की सेटिंग प्राप्त करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | निर्दिष्ट xml-stream से BarCode प्रॉपर्टीज़ इम्पोर्ट करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | निर्दिष्ट xml-file से BarCode प्रॉपर्टीज़ इम्पोर्ट करता है और उन्हें वर्तमान BarCodeReader इंस्टेंस पर लागू करता है। |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | फ़ंक्शन अन्य थ्रेड से वर्तमान मान्यता सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड है और कॉल करने के तुरंत बाद नियंत्रण लौटाता है। जब मान्यता प्रक्रिया बहुत लंबी हो तो इस मेथड का उपयोग किया जाना चाहिए। |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | निर्दिष्ट xml-stream में BarCode प्रॉपर्टीज़ एक्सपोर्ट करता है |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | निर्दिष्ट xml-file में BarCode प्रॉपर्टीज़ एक्सपोर्ट करता है |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | छवि से [`BarCodeResult`](../barcoderesult/) पढ़ता है। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Bitmap) | मान्यता के लिए बिटमैप इमेज सेट करता है। ReadBarCodes() मेथड से पहले इसे कॉल करना आवश्यक है। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(LuminanceFrame) | पहचान के लिए ल्यूमिनेंस फ्रेम सेट करता है। इसे [`ReadBarCodes`](./readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_6)(Stream) | पहचान के लिए इमेज स्ट्रीम सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_7)(string) | पहचान के लिए इमेज फ़ाइल सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(Bitmap, Rectangle) | पहचान के लिए बिटमैप इमेज और क्षेत्र सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_5)(Bitmap, Rectangle[]) | पहचान के लिए बिटमैप इमेज और क्षेत्रों को सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(LuminanceFrame, Rectangle) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्र सेट करता है। इसे [`ReadBarCodes`](./readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(LuminanceFrame, Rectangle[]) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्रों को सेट करता है। इसे [`ReadBarCodes`](./readbarcodes/) मेथड से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/)(params SingleDecodeType[]) | पहचान के लिए [`SingleDecodeType`](../singledecodetype/) प्रकार की एरे सेट करता है। इसे ReadBarCodes() मेथड से पहले कॉल किया जाना चाहिए। |

## उदाहरण

यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे डिटेक्ट करें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: BarCodeReader
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: बरकडरडर एक छव क समहत करत है जसमें एक य कई बरकड ह सकते हैं फर यह बरकड क पत लगने के लए ReadBarCodes ऑपरेशन कर सकत है
type: docs
weight: 60
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

बारकोडरीडर एक छवि को समाहित करता है जिसमें एक या कई बारकोड हो सकते हैं, फिर यह बारकोड का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।

```csharp
public class BarCodeReader : Component
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग डिफ़ॉल्ट मान के साथ। |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` एक छवि से वर्ग. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` फ़ाइल से वर्ग. |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | का एक नया उदाहरण प्रारंभ करता है`BarCodeReader` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | मुख्य बारकोड डिकोडिंग पैरामीटर। ऐसे पैरामीटर शामिल हैं जो मान्यता प्राप्त डेटा पर प्रभाव डालते हैं। |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | पहचाना जाता है[`BarCodeResult`](../barcoderesult/)एस सरणी |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | मान्यता प्राप्त बारकोड गिनती प्राप्त करता है |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | गुणवत्ता सेटिंग्स मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देती हैं। आप एम्बेडेड प्रीसेट द्वारा गुणवत्ता सेटिंग्स को जल्दी से सेट कर सकते हैं: उच्च प्रदर्शन, सामान्य गुणवत्ता, उच्च गुणवत्ता, मैक्सबारकोड या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। गुणवत्ता सेटिंग्स का डिफ़ॉल्ट मान सामान्य गुणवत्ता है। |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | मिलीसेकंड में पहचान प्रक्रिया का टाइमआउट प्राप्त या सेट करता है। |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | प्रोसेसर कोर का उपयोग करने की सेटिंग प्राप्त करता है. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | निर्दिष्ट एक्सएमएल-स्ट्रीम से बारकोड गुण आयात करता है और उन्हें वर्तमान बारकोडरीडर उदाहरण पर लागू करता है। |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | निर्दिष्ट एक्सएमएल-फाइल से बारकोड गुण आयात करता है और उन्हें वर्तमान बारकोडरीडर उदाहरण पर लागू करता है। |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। एबॉर्ट अनब्लॉकेबल मेथड है और कॉल करने के बाद ही कंट्रोल लौटाता है। विधि का उपयोग तब किया जाना चाहिए जब मान्यता प्रक्रिया बहुत लंबी हो। |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | बारकोड गुणों को एक्सएमएल-स्ट्रीम निर्दिष्ट में निर्यात करता है |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | बारकोड गुणों को xml-फ़ाइल निर्दिष्ट में निर्यात करता है |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | पढ़ता है[`BarCodeResult`](../barcoderesult/) एस छवि से. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | पहचान के लिए बिटमैप छवि सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | पहचान के लिए इमेज स्ट्रीम सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | पहचान के लिए छवि फ़ाइल सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | पहचान के लिए बिटमैप छवि और क्षेत्र सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | पहचान के लिए बिटमैप छवि और क्षेत्र सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | पहचान के लिए डिकोड प्रकार सेट करता है। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | सेट[`SingleDecodeType`](../singledecodetype/) मान्यता के लिए सरणी टाइप करें। को ReadBarCodes() विधि से पहले कॉल किया जाना चाहिए। |

### उदाहरण

यह नमूना दिखाता है कि कोड39 और कोड128 बारकोड का पता कैसे लगाया जाए।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

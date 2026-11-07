---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader क्लास"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader क्लास। BarCodeReader एक छवि को समाहित करता है जिसमें एक या कई बारकोड्स हो सकते हैं, और फिर यह C++ में बारकोड्स का पता लगाने के लिए ReadBarCodes ऑपरेशन कर सकता है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Abort](./abort/)() | फ़ंक्शन अन्य थ्रेड से वर्तमान पहचान सत्र को समाप्त करने का अनुरोध करता है। Abort एक अनब्लॉक करने योग्य मेथड है और कॉल करने के तुरंत बाद नियंत्रण लौटाता है। यह मेथड तब उपयोग किया जाना चाहिए जब पहचान प्रक्रिया बहुत लंबी हो। |
| [BarCodeReader](./barcodereader/)() | डिफ़ॉल्ट मानों के साथ [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले इमेज (SetBitmapImage()) सेट करना आवश्यक है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस एक इमेज से इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::String) | [BarCodeReader](./) क्लास का नया इंस्टेंस फ़ाइल से इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | [BarCodeReader](./) क्लास का नया इंस्टेंस ल्यूमिनेंस फ्रेम से इनिशियलाइज़ करता है। |
| [Dispose](./dispose/)() override | संसाधन मुक्त करें |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) गुणों को निर्दिष्ट XML फ़ाइल में निर्यात करता है |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) गुणों को निर्दिष्ट XML स्ट्रीम में निर्यात करता है |
| [get_BarCodeReadType](./get_barcodereadtype/)() | पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को प्राप्त करता है। इसे [ReadBarCodes](./readbarcodes/) कॉल करने से पहले सेट करना आवश्यक है। |
| [get_BarcodeSettings](./get_barcodesettings/)() | मुख्य [BarCode](../../aspose.barcode/) डिकोडिंग पैरामीटर। इसमें ऐसे पैरामीटर शामिल हैं जो पहचाने गए डेटा पर प्रभाव डालते हैं। |
| [get_FoundBarCodes](./get_foundbarcodes/)() | पहचाने गए [BarCodeResult](../barcoderesult/)s की एरे प्राप्त करता है |
| [get_FoundCount](./get_foundcount/)() | पहचाने गए बारकोड्स की गिनती प्राप्त करता है |
| static [get_ProcessorSettings](./get_processorsettings/)() | प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है। |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) मैन्युअल रूप से पहचान गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes द्वारा जल्दी से [QualitySettings](../qualitysettings/) सेट कर सकते हैं या आप अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। [QualitySettings](../qualitysettings/) का डिफ़ॉल्ट मान NormalQuality है। |
| [get_Timeout](./get_timeout/)() | पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में प्राप्त करता है। |
| static [ImportFromXml](./importfromxml/)(System::String) | निर्दिष्ट xml-फ़ाइल से [BarCode](../../aspose.barcode/) गुण आयात करता है और उन्हें वर्तमान [BarCodeReader](./) उदाहरण पर लागू करता है। |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | निर्दिष्ट xml-स्ट्रीम से [BarCode](../../aspose.barcode/) गुण आयात करता है और उन्हें वर्तमान [BarCodeReader](./) उदाहरण पर लागू करता है। |
| [ReadBarCodes](./readbarcodes/)() | छवि से [BarCodeResult](../barcoderesult/) पढ़ता है। |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | पहचान के लिए उपयोग किए जाने वाले बारकोड डिकोड प्रकार को सेट करता है। इसे [ReadBarCodes](./readbarcodes/) को कॉल करने से पहले सेट किया जाना चाहिए। |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) मैन्युअल रूप से पहचान गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes द्वारा जल्दी से [QualitySettings](../qualitysettings/) सेट कर सकते हैं या आप अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। [QualitySettings](../qualitysettings/) का डिफ़ॉल्ट मान NormalQuality है। |
| [set_Timeout](./set_timeout/)(int32_t) | पहचान प्रक्रिया का टाइमआउट मिलीसेकंड में सेट करता है। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | पहचान के लिए बिटमैप छवि सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | पहचान के लिए बिटमैप छवि और क्षेत्रों को सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | पहचान के लिए बिटमैप छवि और क्षेत्र को सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | पहचान के लिए छवि फ़ाइल सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | पहचान के लिए छवि स्ट्रीम सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्र सेट करता है। इसे [ReadBarCodes](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | पहचान के लिए ल्यूमिनेंस फ्रेम और क्षेत्रों को सेट करता है। इसे [ReadBarCodes](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | पहचान के लिए ल्यूमिनेंस फ्रेम सेट करता है। इसे [ReadBarCodes](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [SingleDecodeType](../singledecodetype/) प्रकार एरे को पहचान के लिए सेट करता है। इसे [ReadBarCodes()](./readbarcodes/) मेथड को कॉल करने से पहले बुलाया जाना चाहिए। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि Code39 और Code128 बारकोड कैसे पहचानें।
```cpp
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

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

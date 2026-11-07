---
title: "विधि"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। C++ में कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करता है।"
type: docs
weight: 700
url: /hi/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करें।

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | कोडटेक्स्ट के बाइट्स |

## और देखें

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | System::String | CodeText स्ट्रिंग |
| एन्कोडिंग | System::SharedPtr\<System::Text::Encoding\> | लागू किया गया एन्कोडिंग |
## टिप्पणियाँ


निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करती है, तो फ़ंक्शन स्वचालित रूप से एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) सम्मिलित करता है।

यह फ़ंक्शन केवल 2D बारकोड्स (जैसे Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके Unicode टेक्स्ट को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, आधुनिक अनुप्रयोगों में इस मेथड को पुराना माना जाता है। आधुनिक उपयोग मामलों के लिए Unicode डेटा के लिए [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) एन्कोडिंग की सिफ़ारिश की जाती है।

इस फ़ंक्शन का उपयोग 1D बारकोड्स, GS1-अनुपालन बारकोड्स (जिसमें 2D शामिल है), या HIBC बारकोड्स (जिसमें 2D शामिल है) के साथ करने पर संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम उत्पन्न हो सकते हैं।


यह उदाहरण दिखाता है कि विभिन्न एन्कोडिंग का उपयोग करके 2D बारकोड्स के लिए Unicode-एन्कोडेड टेक्स्ट सेट करने हेतु **SetCodeText** का कैसे उपयोग किया जाता है:


```cpp
[C#]
//UTF-8 के साथ BOM का उपयोग करके QR कोड टेक्स्ट एन्कोड करें
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Shift-JIS (जापानी एन्कोडिंग) का उपयोग करके DataMatrix टेक्स्ट एन्कोड करें
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## और देखें

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | System::String | CodeText स्ट्रिंग |
| एन्कोडिंग | System::SharedPtr\<System::Text::Encoding\> | लागू किया गया एन्कोडिंग |
| insertBOM | bool | निर्दिष्ट एन्कोडिंग (जैसे UTF-8, UTF-16, UTF-32) के समर्थन में होने पर बाइट ऑर्डर मार्क (BOM) सम्मिलित करने का संकेत देता है। यदि **true** सेट किया जाता है, तो BOM जोड़ा जाता है; यदि **false** सेट किया जाता है, तो BOM को छोड़ दिया जाता है भले ही एन्कोडिंग सामान्यतः इसका उपयोग करती हो। |
## टिप्पणियाँ


निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करती है और **insertBOM** **true** पर सेट है, तो फ़ंक्शन एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) सम्मिलित करता है।

यह फ़ंक्शन केवल 2D बारकोड्स (जैसे Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि) के साथ उपयोग के लिए अभिप्रेत है। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके Unicode टेक्स्ट को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, आधुनिक अनुप्रयोगों में इस मेथड को पुराना माना जाता है। आधुनिक उपयोग मामलों के लिए Unicode डेटा के लिए [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) एन्कोडिंग की सिफ़ारिश की जाती है।

इस फ़ंक्शन का उपयोग 1D बारकोड्स, GS1-अनुपालन बारकोड्स (जिसमें 2D शामिल है), या HIBC बारकोड्स (जिसमें 2D शामिल है) के साथ करने पर संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम उत्पन्न हो सकते हैं।


यह उदाहरण दिखाता है कि 2D बारकोड्स के लिए **SetCodeText** का उपयोग BOM के साथ या बिना कैसे किया जाता है।


```cpp
[C#]
    //UTF-8 with BOM का उपयोग करके कोडटेक्स्ट एन्कोड करें
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //UTF-8 without BOM का उपयोग करके कोडटेक्स्ट एन्कोड करें
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## और देखें

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "BarcodeGenerator.SetCodeText"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarcodeGenerator मेथड। कोडटेक्स्ट को बाइट्स की श्रृंखला के रूप में सेट करें"
type: docs
weight: 100
url: /hi/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

codetext को बाइट अनुक्रम के रूप में सेट करें।

```csharp
public void SetCodeText(byte[] codeBytes)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeBytes | Byte[] | कोडटेक्स्ट के बाइट्स |

### और देखें

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करता है, तो फ़ंक्शन स्वचालित रूप से एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) सम्मिलित करता है।

यह फ़ंक्शन केवल 2D बारकोड के साथ उपयोग के लिए अभिप्रेत है (उदा., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि)। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके यूनिकोड टेक्स्ट को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, यूनिकोड डेटा के लिए [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) एन्कोडिंग की सिफ़ारिश की जाती है।

इस फ़ंक्शन को 1D बारकोड, GS1‑अनुपालन बारकोड (जिसमें 2D शामिल हैं), या HIBC बारकोड (जिसमें 2D शामिल हैं) के साथ उपयोग करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम मिल सकते हैं।

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | स्ट्रिंग | CodeText स्ट्रिंग |
| एन्कोडिंग | एन्कोडिंग | प्रयुक्त एन्कोडिंग |

## उदाहरण

यह उदाहरण दिखाता है कि विभिन्न एन्कोडिंग का उपयोग करके 2D बारकोड के लिए यूनिकोड‑एन्कोडेड टेक्स्ट सेट करने के लिए `SetCodeText` कैसे उपयोग किया जाता है:

```csharp
[C#]
//UTF-8 with BOM का उपयोग करके QR कोड टेक्स्ट एन्कोड करें
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

### और देखें

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

निर्दिष्ट **encoding** का उपयोग करके Unicode **codeText** को बाइट अनुक्रम में एन्कोड करता है। UTF-8 सबसे अधिक उपयोग किया जाने वाला एन्कोडिंग है। यदि एन्कोडिंग इसे समर्थन करता है और **insertBOM** `true` पर सेट है, तो फ़ंक्शन एक [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) शामिल करता है।

यह फ़ंक्शन केवल 2D बारकोड के साथ उपयोग के लिए अभिप्रेत है (उदा., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, आदि)। यह राष्ट्रीय या विशेष एन्कोडिंग का उपयोग करके यूनिकोड टेक्स्ट को मैन्युअल रूप से एन्कोड करने की सुविधा देता है; हालांकि, यह विधि आधुनिक अनुप्रयोगों में पुरानी मानी जाती है। आधुनिक उपयोग मामलों के लिए, यूनिकोड डेटा के लिए [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) एन्कोडिंग की सिफ़ारिश की जाती है।

इस फ़ंक्शन को 1D बारकोड, GS1‑अनुपालन बारकोड (जिसमें 2D शामिल हैं), या HIBC बारकोड (जिसमें 2D शामिल हैं) के साथ उपयोग करना संबंधित बारकोड मानकों द्वारा समर्थित नहीं है और इससे अप्रत्याशित परिणाम मिल सकते हैं।

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codeText | स्ट्रिंग | CodeText स्ट्रिंग |
| एन्कोडिंग | एन्कोडिंग | प्रयुक्त एन्कोडिंग |
| insertBOM | Boolean | निर्देश देता है कि क्या निर्दिष्ट एन्कोडिंग द्वारा समर्थित होने पर बाइट ऑर्डर मार्क (BOM) डालना है (उदा., UTF-8, UTF-16, UTF-32)। यदि `true` पर सेट किया जाता है, तो BOM जोड़ा जाता है; यदि `false` पर सेट किया जाता है, तो एन्कोडिंग सामान्यतः BOM का उपयोग करती हो, तब भी इसे छोड़ दिया जाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि 2D बारकोड के लिए BOM के साथ या बिना `SetCodeText` कैसे उपयोग किया जाता है।

```csharp
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

### और देखें

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)



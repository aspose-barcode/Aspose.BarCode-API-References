---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 3900
url: /hi/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | 0 | सभी बारकोड प्रकारों के लिए उल्टे चित्रों पर बारकोड की अतिरिक्त पहचान को अक्षम करता है, सिवाय [QR](../../aspose.barcode.barcoderecognition.qr/) कोड के। |
| अक्षम किया गया | 1 | उल्टे चित्रों पर बारकोड की अतिरिक्त पहचान को अक्षम करता है। |
| सक्षम किया गया | 2 | उल्टे चित्रों पर बारकोड की अतिरिक्त पहचान को सक्षम करता है |

## टिप्पणियाँ


वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

यह उदाहरण दिखाता है कि InverseImage मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

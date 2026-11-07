---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 3700
url: /hi/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | वर्तमान में Disabled के समान। रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है। |
| अक्षम किया गया | 1 | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है। |
| सक्षम किया गया | 2 | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को सक्षम करता है। |

## टिप्पणियाँ


वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

यह उदाहरण दिखाता है कि ComplexBackground मोड का उपयोग कैसे करें
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. वह मोड जो उल्टे रंग चमक वाले चित्रों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।"
type: docs
weight: 270
url: /hi/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

उल्टे रंग (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त मान्यता को सक्षम या अक्षम करने वाला मोड।

```csharp
public enum InverseImageMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | QR कोड को छोड़कर सभी बारकोड प्रकारों के लिए उल्टे चित्रों पर अतिरिक्त बारकोड पहचान को अक्षम करता है। |
| Disabled | `1` | उल्टे चित्रों पर अतिरिक्त बारकोड पहचान को अक्षम करता है। |
| Enabled | `2` | उल्टे चित्रों पर अतिरिक्त बारकोड पहचान को सक्षम करता है |

## उदाहरण

यह उदाहरण InverseImage मोड का उपयोग कैसे करें दिखाता है।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



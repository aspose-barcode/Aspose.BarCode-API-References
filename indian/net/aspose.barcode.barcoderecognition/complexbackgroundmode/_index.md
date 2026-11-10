---
title: "एनम ComplexBackgroundMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode एनम। वह मोड जो रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को सक्षम या अक्षम करता है।"
type: docs
weight: 200
url: /hi/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त मान्यता को सक्षम या अक्षम करने वाला मोड।

```csharp
public enum ComplexBackgroundMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | इस समय यह Disabled के समान है। रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है। |
| Disabled | `1` | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को अक्षम करता है। |
| Enabled | `2` | रंगीन छवियों पर अतिरिक्त रंग बारकोड पहचान को सक्षम करता है। |

## उदाहरण

यह नमूना दिखाता है कि ComplexBackground मोड का उपयोग कैसे किया जाता है

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



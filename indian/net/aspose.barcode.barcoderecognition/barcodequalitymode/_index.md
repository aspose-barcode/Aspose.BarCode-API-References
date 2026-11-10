---
title: "Enum BarcodeQualityMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode enum. वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए मेथड्स को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्वों को पहचानने के लिए अधिक जटिल मेथड्स की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है।"
type: docs
weight: 110
url: /hi/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

एक मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक जटिल विधियों की आवश्यकता होती है जो मान्यता को धीमा कर देती हैं।

```csharp
public enum BarcodeQualityMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| High | `0` | उच्च गुणवत्ता वाले बारकोड के लिए पहचान मेथड्स को सक्षम करता है। |
| Normal | `1` | सामान्य (नॉर्मल) गुणवत्ता वाले बारकोड के लिए पहचान मेथड्स को सक्षम करता है। |
| Low | `2` | निम्न गुणवत्ता वाले बारकोड के लिए पहचान मेथड्स को सक्षम करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि BarcodeQuality मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



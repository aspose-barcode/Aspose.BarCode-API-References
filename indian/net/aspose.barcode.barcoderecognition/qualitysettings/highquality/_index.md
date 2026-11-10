---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "QualitySettings प्रॉपर्टी। HighQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। यह अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है।"
type: docs
weight: 20
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है।

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality पहचान गुणवत्ता प्रीसेट.

## उदाहरण

यह नमूना दिखाता है कि HighQuality मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



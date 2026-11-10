---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "QualitySettings प्रॉपर्टी। NormalQuality पहचान गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त"
type: docs
weight: 40
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality मान्यता गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त है।

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality पहचान गुणवत्ता प्रीसेट.

## उदाहरण

यह नमूना दिखाता है कि NormalQuality मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



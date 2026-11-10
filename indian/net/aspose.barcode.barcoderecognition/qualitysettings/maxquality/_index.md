---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "QualitySettings प्रॉपर्टी। MaxQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को पहचानने के लिए विकसित किया गया है"
type: docs
weight: 30
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को भी पहचानने के लिए विकसित किया गया है।

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality पहचान गुणवत्ता प्रीसेट.

## उदाहरण

यह नमूना दिखाता है कि MaxQuality मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



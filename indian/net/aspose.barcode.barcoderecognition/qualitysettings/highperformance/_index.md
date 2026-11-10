---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "QualitySettings प्रॉपर्टी। HighPerformance पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह पहचाने जाते हैं।"
type: docs
weight: 10
url: /hi/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance मान्यता गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं।

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance पहचान गुणवत्ता प्रीसेट।

## उदाहरण

यह उदाहरण दिखाता है कि HighPerformance मोड का उपयोग कैसे करें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



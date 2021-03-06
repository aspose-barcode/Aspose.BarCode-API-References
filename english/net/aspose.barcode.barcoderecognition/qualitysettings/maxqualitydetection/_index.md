---
title: MaxQualityDetection
second_title: Aspose.BarCode for .NET API Reference
description: 
type: docs
weight: 50
url: /net/aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/
---
## QualitySettings.MaxQualityDetection property

MaxQualityDetection recognition quality preset. Same as NormalQuality but with highest quality [`DetectorSettings`](../detectorsettings). Allows to detect diagonal and damaged barcodes.

```csharp
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
    reader.QualitySettings = QualitySettings.MaxQualityDetection;
```

```csharp
public static QualitySettings MaxQualityDetection { get; }
```

### Property Value

MaxQualityDetection recognition quality preset.

### See Also

* class [QualitySettings](../../qualitysettings)
* namespace [Aspose.BarCode.BarCodeRecognition](../../qualitysettings)
* assembly [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

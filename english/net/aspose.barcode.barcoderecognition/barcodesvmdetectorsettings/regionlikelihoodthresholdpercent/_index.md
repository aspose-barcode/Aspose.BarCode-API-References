---
title: BarcodeSvmDetectorSettings.RegionLikelihoodThresholdPercent
second_title: Aspose.BarCode for .NET API Reference
description: BarcodeSvmDetectorSettings property. Sets threshold for detected regions that may contain barcodes
type: docs
weight: 50
url: /net/aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/regionlikelihoodthresholdpercent/
---
## BarcodeSvmDetectorSettings.RegionLikelihoodThresholdPercent property

Sets threshold for detected regions that may contain barcodes.

Value 0.7 means that bottom 70% of possible regions are filtered out and not processed further. Region likelihood threshold must be between [0.05, 0.9] Use high values for clear images with few barcodes. Use low values for images with many barcodes or for noisy images. Low value may lead to a bigger recognition time.

```csharp
public float RegionLikelihoodThresholdPercent { get; set; }
```

### See Also

* class [BarcodeSvmDetectorSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



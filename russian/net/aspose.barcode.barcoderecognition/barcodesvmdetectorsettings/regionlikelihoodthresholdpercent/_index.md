---
title: RegionLikelihoodThresholdPercent
second_title: Справочник по API Aspose.BarCode для .NET
description: Устанавливает порог для обнаруженных областей которые могут содержать штрих-коды.
type: docs
weight: 50
url: /ru/net/aspose.barcode.barcoderecognition/barcodesvmdetectorsettings/regionlikelihoodthresholdpercent/
---
## BarcodeSvmDetectorSettings.RegionLikelihoodThresholdPercent property

Устанавливает порог для обнаруженных областей, которые могут содержать штрих-коды.

Значение 0,7 означает, что нижние 70% возможных областей отфильтровываются и не обрабатываются дальше. Порог вероятности области должен быть между [0,05, 0,9] Используйте высокие значения для четких изображений с небольшим количеством штрих-кодов. Используйте низкие значения для изображений с большим количеством штрих-кодов. штрих-кодов или зашумленных изображений. Низкое значение может привести к увеличению времени распознавания.

```csharp
public float RegionLikelihoodThresholdPercent { get; set; }
```

### Смотрите также

* class [BarcodeSvmDetectorSettings](../../barcodesvmdetectorsettings)
* пространство имен [Aspose.BarCode.BarCodeRecognition](../../barcodesvmdetectorsettings)
* сборка [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

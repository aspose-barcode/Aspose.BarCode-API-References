---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarCodeReader özelliği. İşlemci çekirdeklerini kullanma ayarlarını alır"
type: docs
weight: 140
url: /tr/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

İşlemci çekirdeklerinin kullanım ayarlarını alır.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Örnekler

Bu örnek, ProcessorSettings'i kullanarak maksimum çok iş parçacıklı performans eklemenin nasıl yapılacağını gösterir

```csharp
[C#]
//Bu, tek bir BarCodeReader çağrısı için tüm çekirdeklerin kullanılmasını sağlar
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Bu, mevcut çekirdek sayısının kullanılmasını sağlar
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Ayrıca Bakınız

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



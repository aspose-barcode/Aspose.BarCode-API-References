---
title: "metot"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. C++'da işlemci çekirdeklerinin kullanım ayarlarını alır."
type: docs
weight: 100
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


İşlemci çekirdeklerinin kullanım ayarını alır.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Açıklamalar


Bu örnek, ProcessorSettings'i kullanarak maksimum çok iş parçacıklı performans eklemeyi gösterir.
```cpp
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

## Ayrıca Bakınız

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

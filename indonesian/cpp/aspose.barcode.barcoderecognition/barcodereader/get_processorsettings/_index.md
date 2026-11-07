---
title: "metode"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. Mendapatkan pengaturan penggunaan inti prosesor dalam C++."
type: docs
weight: 100
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Mendapatkan pengaturan penggunaan inti prosesor.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Catatan


Contoh ini menunjukkan cara menggunakan ProcessorSettings untuk menambahkan kinerja multi-threaded maksimum
```cpp
[C#]
//ini memungkinkan penggunaan semua inti untuk satu panggilan BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//ini memungkinkan penggunaan jumlah inti saat ini
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Lihat Juga

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "μέθοδος"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "μέθοδος. Λαμβάνει τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή σε C++."
type: docs
weight: 100
url: /el/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Λαμβάνει τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το ProcessorSettings για να προσθέσετε μέγιστη πολυνηματική απόδοση
```cpp
[C#]
//αυτό επιτρέπει τη χρήση όλων των πυρήνων για μία κλήση BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//αυτό επιτρέπει τη χρήση του τρέχοντος αριθμού πυρήνων
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Δείτε επίσης

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

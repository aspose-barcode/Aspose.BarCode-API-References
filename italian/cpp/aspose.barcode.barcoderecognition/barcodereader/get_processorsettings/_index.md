---
title: "method"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Ottiene le impostazioni dell'uso dei core del processore in C++."
type: docs
weight: 100
url: /it/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Ottiene le impostazioni per l'uso dei core del processore.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Osservazioni


Questo esempio mostra come utilizzare ProcessorSettings per aggiungere la massima prestazione multithread.
```cpp
[C#]
//ciò consente di utilizzare tutti i core per una singola chiamata a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//ciò consente di utilizzare il numero corrente di core
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Vedi anche

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

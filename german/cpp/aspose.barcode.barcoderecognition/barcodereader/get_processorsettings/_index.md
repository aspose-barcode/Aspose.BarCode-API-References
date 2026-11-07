---
title: "Methode"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Gibt eine Einstellung zur Nutzung von Prozessorkernen in C++ zurück."
type: docs
weight: 100
url: /de/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Ermittelt die Einstellung zur Nutzung von Prozessorkernen.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Hinweise


Dieses Beispiel zeigt, wie man ProcessorSettings verwendet, um maximale Multi-Thread-Leistung hinzuzufügen.
```cpp
[C#]
//Dies ermöglicht die Nutzung aller Kerne für einen einzelnen BarCodeReader-Aufruf.
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Dies ermöglicht die Nutzung der aktuellen Kernanzahl.
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Siehe auch

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

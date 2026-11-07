---
title: "methode"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Haalt een instelling op voor het gebruik van processorkernen in C++."
type: docs
weight: 100
url: /nl/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Haalt een instelling op voor het gebruik van processorcores.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Opmerkingen


Dit voorbeeld toont hoe ProcessorSettings te gebruiken om maximale multi-threaded prestaties toe te voegen
```cpp
[C#]
//dit maakt het mogelijk om alle cores te gebruiken voor één BarCodeReader-aanroep
BarCodeReader.ProcessorSettings.UseAllCores = true;
//dit maakt het mogelijk om het huidige aantal cores te gebruiken
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Zie ook

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

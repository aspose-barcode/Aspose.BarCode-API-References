---
title: "metod"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar en inställning för användning av processorkärnor i C++."
type: docs
weight: 100
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


Hämtar en inställning för att använda processorkärnor.

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## Anmärkningar


Detta exempel visar hur man använder ProcessorSettings för att lägga till maximal flertrådad prestanda
```cpp
[C#]
//detta möjliggör att använda alla kärnor för ett enskilt BarCodeReader-anrop
BarCodeReader.ProcessorSettings.UseAllCores = true;
//detta möjliggör att använda det aktuella antalet kärnor
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Se även

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

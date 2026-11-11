---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "BarCodeReader eigenschap. Haalt een instelling op voor het gebruik van processor-cores"
type: docs
weight: 140
url: /nl/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Haalt een instelling op voor het gebruik van processorkernen.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Voorbeelden

Dit voorbeeld toont hoe ProcessorSettings te gebruiken om maximale multi-threaded prestaties toe te voegen

```csharp
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

### Zie ook

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



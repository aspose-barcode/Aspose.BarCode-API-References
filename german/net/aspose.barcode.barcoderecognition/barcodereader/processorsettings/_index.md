---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarCodeReader-Eigenschaft. Gibt die Einstellungen zur Nutzung von Prozessorkernen zurück"
type: docs
weight: 140
url: /de/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Liest die Einstellung zur Nutzung von Prozessorkernen.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Beispiele

Dieses Beispiel zeigt, wie man ProcessorSettings verwendet, um maximale Multi-Thread-Leistung hinzuzufügen

```csharp
[C#]
//Dies ermöglicht die Nutzung aller Kerne für einen einzelnen BarCodeReader-Aufruf
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Dies ermöglicht die Nutzung der aktuellen Kernanzahl
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Siehe auch

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



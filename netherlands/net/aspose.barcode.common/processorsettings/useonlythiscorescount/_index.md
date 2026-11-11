---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "ProcessorSettings-eigenschap. Specificeer het aantal cores dat gebruikt moet worden. U moet de eigenschap UseAllCores op false zetten"
type: docs
weight: 30
url: /nl/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Specificeer het aantal cores dat gebruikt moet worden. Je moet de eigenschap "UseAllCores" wijzigen naar "false".

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## Voorbeelden

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Zie ook

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)



---
title: UseOnlyThisCoresCount
second_title: Aspose.BarCode für .NET-API-Referenz
description: Geben Sie die Anzahl der zu verwendenden Kerne an. Sie müssen die Eigenschaft UseAllCores auf false ändern.
type: docs
weight: 30
url: /de/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Geben Sie die Anzahl der zu verwendenden Kerne an. Sie müssen die Eigenschaft "UseAllCores" auf "false" ändern.

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

### Beispiele

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Siehe auch

* class [ProcessorSettings](../../processorsettings)
* namensraum [Aspose.BarCode.Common](../../processorsettings)
* Montage [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
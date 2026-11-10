---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété ProcessorSettings. Spécifie le nombre de cœurs à utiliser. Vous devez changer la propriété UseAllCores à false."
type: docs
weight: 30
url: /fr/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Spécifiez le nombre de cœurs à utiliser. Vous devez changer la propriété "UseAllCores" en "false".

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## Exemples

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Voir aussi

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)



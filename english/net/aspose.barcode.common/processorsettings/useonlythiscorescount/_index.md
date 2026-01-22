---
title: ProcessorSettings.UseOnlyThisCoresCount
second_title: Aspose.BarCode for .NET API Reference
description: ProcessorSettings property. Specify the number of cores to use. You need to change the property UseAllCores to false
type: docs
weight: 30
url: /net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Specify the number of cores to use. You need to change the property "UseAllCores" to "false".

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## Examples

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### See Also

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)



---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "ProcessorSettings özelliği. Kullanılacak çekirdek sayısını belirtin. UseAllCores özelliğini false olarak değiştirmeniz gerekir"
type: docs
weight: 30
url: /tr/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir.

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## Örnekler

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Ayrıca Bakınız

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)



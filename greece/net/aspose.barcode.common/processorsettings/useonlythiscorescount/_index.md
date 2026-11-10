---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "ProcessorSettings ιδιότητα. Καθορίστε τον αριθμό πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα UseAllCores σε false"
type: docs
weight: 30
url: /el/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false".

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## Παραδείγματα

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Δείτε επίσης

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)



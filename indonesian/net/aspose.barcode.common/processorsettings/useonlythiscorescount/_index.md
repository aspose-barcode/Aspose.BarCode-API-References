---
title: UseOnlyThisCoresCount
second_title: Aspose.BarCode untuk .NET API Referensi
description: Tentukan jumlah core yang akan digunakan. Anda perlu mengubah properti UseAllCores menjadi false.
type: docs
weight: 30
url: /id/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Tentukan jumlah core yang akan digunakan. Anda perlu mengubah properti "UseAllCores" menjadi "false".

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

### Contoh

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Lihat juga

* class [ProcessorSettings](../)
* ruang nama [Aspose.BarCode.Common](../../processorsettings/)
* perakitan [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

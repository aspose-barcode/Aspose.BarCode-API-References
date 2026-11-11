---
title: "Klasse ProcessorSettings"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Common.ProcessorSettings klasse. ProcessorSettings maken het mogelijk om barcodes te herkennen met multithreaded prestatieverbetering."
type: docs
weight: 470
url: /nl/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings maakt het mogelijk barcodes te herkennen met een multi‑threaded prestatieverbetering.

```csharp
public class ProcessorSettings
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Specificeer het maximale aantal extra threads om code parallel uit te voeren |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Is nodig om alle cores te gebruiken. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Specificeer het aantal cores dat gebruikt moet worden. Je moet de eigenschap "UseAllCores" wijzigen naar "false". |

## Voorbeelden

Dit voorbeeld toont hoe ProcessorSettings te gebruiken om maximale multi-threaded prestaties toe te voegen

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//dit maakt het mogelijk om alle cores te gebruiken voor één BarCodeReader-aanroep
BarCodeReader.ProcessorSettings.UseAllCores = true;
//dit maakt het mogelijk om het huidige aantal cores te gebruiken
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
Dim workerThreads As Integer = Environment.ProcessorCount * 2
Dim portThreads As Integer = Environment.ProcessorCount * 2
System.Threading.ThreadPool.GetMinThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads)
System.Threading.ThreadPool.GetMaxThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads)
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2

'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Zie ook

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



---
title: "Klasse ProcessorSettings"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Common.ProcessorSettings class. ProcessorSettings ermöglichen die Erkennung von Barcodes mit multithreaded Leistungssteigerung"
type: docs
weight: 470
url: /de/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings ermöglichen die Erkennung von Barcodes mit mehrthreadiger Leistungssteigerung.

```csharp
public class ProcessorSettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Geben Sie die maximale Anzahl zusätzlicher Threads an, um Code parallel auszuführen |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Wird benötigt, um alle Kerne zu nutzen. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Geben Sie die zu verwendende Kernanzahl an. Sie müssen die Eigenschaft "UseAllCores" auf "false" ändern. |

## Beispiele

Dieses Beispiel zeigt, wie man ProcessorSettings verwendet, um maximale Multi-Thread-Leistung hinzuzufügen

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//Dies ermöglicht die Nutzung aller Kerne für einen einzelnen BarCodeReader-Aufruf
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Dies ermöglicht die Nutzung der aktuellen Kernanzahl
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

### Siehe auch

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



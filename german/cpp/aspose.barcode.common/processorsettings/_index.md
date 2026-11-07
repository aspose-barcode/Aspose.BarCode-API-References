---
title: "Aspose::BarCode::Common::ProcessorSettings Klasse"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Common::ProcessorSettings Klasse. ProcessorSettings ermöglichen das Erkennen von Barcodes mit mehrthreadiger Leistungssteigerung der Performance in C++."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Geben Sie die maximale Anzahl zusätzlicher Threads an, um Code parallel auszuführen. |
| [get_UseAllCores](./get_useallcores/)() const | Wird benötigt, um alle Kerne zu nutzen. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Geben Sie die zu verwendende Kernanzahl an. Sie müssen die Eigenschaft "UseAllCores" auf "false" ändern. |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Geben Sie die maximale Anzahl zusätzlicher Threads an, um Code parallel auszuführen. |
| [set_UseAllCores](./set_useallcores/)(bool) | Wird benötigt, um alle Kerne zu nutzen. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Geben Sie die zu verwendende Kernanzahl an. Sie müssen die Eigenschaft "UseAllCores" auf "false" ändern. |
## Hinweise


Dieses Beispiel zeigt, wie man [ProcessorSettings](./) verwendet, um maximale mehrthreadige Leistung hinzuzufügen.
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//Dies ermöglicht die Nutzung aller Kerne für einen einzelnen BarCodeReader-Aufruf.
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Dies ermöglicht die Nutzung der aktuellen Kernanzahl.
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

## Siehe auch

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

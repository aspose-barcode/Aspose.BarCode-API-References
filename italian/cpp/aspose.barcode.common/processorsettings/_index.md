---
title: "Aspose::BarCode::Common::ProcessorSettings class"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Common::ProcessorSettings class. ProcessorSettings consente di riconoscere i codici a barre con aumento delle prestazioni multithread in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Specifica il numero massimo di thread aggiuntivi per eseguire il codice in parallelo |
| [get_UseAllCores](./get_useallcores/)() const | È necessario per utilizzare tutti i core. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Specifica il numero di core da utilizzare. È necessario modificare la proprietà "UseAllCores" in "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Specifica il numero massimo di thread aggiuntivi per eseguire il codice in parallelo |
| [set_UseAllCores](./set_useallcores/)(bool) | È necessario per utilizzare tutti i core. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Specifica il numero di core da utilizzare. È necessario modificare la proprietà "UseAllCores" in "false". |
## Osservazioni


Questo esempio mostra come utilizzare [ProcessorSettings](./) per aggiungere la massima prestazione multithread
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//ciò consente di utilizzare tutti i core per una singola chiamata a BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//ciò consente di utilizzare il numero corrente di core
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

## Vedi anche

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

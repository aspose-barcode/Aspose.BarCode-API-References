---
title: Aspose::BarCode::Common::ProcessorSettings class
linktitle: ProcessorSettings
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Common::ProcessorSettings class. ProcessorSettings allow to recognize barcodes with multi-threaded increasing of performance in C++.'
type: docs
weight: 100
url: /cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Specify the maximal number of additional threads to run code in parallel |
| [get_UseAllCores](./get_useallcores/)() const | Is needed to use all cores. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Specify the number of cores to use. You need to change the property "UseAllCores" to "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Specify the maximal number of additional threads to run code in parallel |
| [set_UseAllCores](./set_useallcores/)(bool) | Is needed to use all cores. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Specify the number of cores to use. You need to change the property "UseAllCores" to "false". |
## Remarks


This sample shows how to use [ProcessorSettings](./) to add maximum multi-threaded performnce 
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = true;
//this allows to use current count of cores
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

## See Also

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

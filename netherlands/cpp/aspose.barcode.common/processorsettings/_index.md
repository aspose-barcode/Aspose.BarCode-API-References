---
title: "Aspose::BarCode::Common::ProcessorSettings class"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Common::ProcessorSettings class. ProcessorSettings maakt het mogelijk om barcodes te herkennen met multi-threaded prestatieverbetering in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Specificeer het maximale aantal extra threads om code parallel uit te voeren |
| [get_UseAllCores](./get_useallcores/)() const | Is nodig om alle cores te gebruiken. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Specificeer het aantal te gebruiken cores. U moet de eigenschap "UseAllCores" wijzigen naar "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Specificeer het maximale aantal extra threads om code parallel uit te voeren |
| [set_UseAllCores](./set_useallcores/)(bool) | Is nodig om alle cores te gebruiken. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Specificeer het aantal te gebruiken cores. U moet de eigenschap "UseAllCores" wijzigen naar "false". |
## Opmerkingen


Dit voorbeeld toont hoe [ProcessorSettings](./) te gebruiken om maximale multi-threaded prestaties toe te voegen
```cpp
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

## Zie ook

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

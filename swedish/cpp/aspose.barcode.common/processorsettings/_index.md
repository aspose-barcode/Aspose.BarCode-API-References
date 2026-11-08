---
title: "Aspose::BarCode::Common::ProcessorSettings-klass"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Common::ProcessorSettings-klass. ProcessorSettings möjliggör igenkänning av streckkoder med flerkärnig prestandaförbättring i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Ange det maximala antalet extra trådar för att köra kod parallellt |
| [get_UseAllCores](./get_useallcores/)() const | Behövs för att använda alla kärnor. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Ange antalet kärnor som ska användas. Du måste ändra egenskapen "UseAllCores" till "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Ange det maximala antalet extra trådar för att köra kod parallellt |
| [set_UseAllCores](./set_useallcores/)(bool) | Behövs för att använda alla kärnor. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Ange antalet kärnor som ska användas. Du måste ändra egenskapen "UseAllCores" till "false". |
## Anmärkningar


Detta exempel visar hur man använder [ProcessorSettings](./) för att lägga till maximal flerkärnig prestanda
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//detta möjliggör att använda alla kärnor för ett enskilt BarCodeReader-anrop
BarCodeReader.ProcessorSettings.UseAllCores = true;
//detta möjliggör att använda det aktuella antalet kärnor
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

## Se även

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

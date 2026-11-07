---
title: "Класс Aspose::BarCode::Common::ProcessorSettings"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::Common::ProcessorSettings. ProcessorSettings позволяют распознавать штрихкоды с многопоточным повышением производительности в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Укажите максимальное количество дополнительных потоков для параллельного выполнения кода |
| [get_UseAllCores](./get_useallcores/)() const | Необходимо для использования всех ядер. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Укажите количество ядер для использования. Необходимо изменить свойство "UseAllCores" на "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Укажите максимальное количество дополнительных потоков для параллельного выполнения кода |
| [set_UseAllCores](./set_useallcores/)(bool) | Необходимо для использования всех ядер. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Укажите количество ядер для использования. Необходимо изменить свойство "UseAllCores" на "false". |
## Примечания


Этот пример показывает, как использовать [ProcessorSettings](./) для добавления максимальной многопоточной производительности
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//это позволяет использовать все ядра для одного вызова BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//это позволяет использовать текущее количество ядер
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

## См. также

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

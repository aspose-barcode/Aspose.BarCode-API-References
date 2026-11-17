---
title: "Aspose::BarCode::Common::ProcessorSettings 类"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Common::ProcessorSettings 类。ProcessorSettings 允许在 C++ 中通过多线程提升性能来识别条形码。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | 指定要并行运行代码的最大附加线程数 |
| [get_UseAllCores](./get_useallcores/)() const | 需要使用所有核心。 |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | 指定要使用的核心数。您需要将属性 "UseAllCores" 更改为 "false"。 |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | 指定要并行运行代码的最大附加线程数 |
| [set_UseAllCores](./set_useallcores/)(bool) | 需要使用所有核心。 |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | 指定要使用的核心数。您需要将属性 "UseAllCores" 更改为 "false"。 |
## 备注


此示例展示了如何使用 [ProcessorSettings](./) 来实现最大多线程性能
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//这允许在单次 BarCodeReader 调用中使用所有核心
BarCodeReader.ProcessorSettings.UseAllCores = true;
//这允许使用当前核心数
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

## 另见

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "类 ProcessorSettings"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Common.ProcessorSettings 类。ProcessorSettings 允许通过多线程提升性能来识别条形码。"
type: docs
weight: 470
url: /zh/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings 允许通过多线程提升性能来识别条码。

```csharp
public class ProcessorSettings
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | 指定并行运行代码时的最大附加线程数 |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | 需要使用所有核心。 |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | 指定要使用的核心数。您需要将属性 "UseAllCores" 更改为 "false"。 |

## 示例

此示例展示了如何使用 ProcessorSettings 来提升最大多线程性能

```csharp
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
//这允许使用当前的核心数
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

### 另见

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



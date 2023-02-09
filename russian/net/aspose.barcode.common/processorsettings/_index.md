---
title: ProcessorSettings
second_title: Справочник по API Aspose.BarCode для .NET
description: ProcessorSettings позволяют распознавать штрих-коды с многопоточным увеличением производительности
type: docs
weight: 290
url: /ru/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings позволяют распознавать штрих-коды с многопоточным увеличением производительности

```csharp
public class ProcessorSettings
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads) { get; set; } | Укажите максимальное количество дополнительных потоков для запуска кода в parallel |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores) { get; set; } | Необходим для использования всех ядер. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount) { get; set; } | Укажите количество используемых ядер. Вам нужно изменить свойство «UseAllCores» на «false». |

### Примеры

В этом примере показано, как использовать ProcessorSettings для добавления максимальной многопоточной производительности

```csharp
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

'это позволяет использовать все ядра для одного вызова BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = True
'это позволяет использовать текущее количество ядер
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Смотрите также

* пространство имен [Aspose.BarCode.Common](../../aspose.barcode.common)
* сборка [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
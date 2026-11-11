---
title: "ProcessorSettings Sınıfı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Common.ProcessorSettings sınıfı. ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımayı sağlar"
type: docs
weight: 470
url: /tr/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımayı sağlar.

```csharp
public class ProcessorSettings
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Kodun paralel olarak çalıştırılacağı ek iş parçacıklarının azami sayısını belirtin |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Tüm çekirdeklerin kullanılabilmesi için gereklidir. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir. |

## Örnekler

Bu örnek, ProcessorSettings'i kullanarak maksimum çok iş parçacıklı performans eklemenin nasıl yapılacağını gösterir

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//Bu, tek bir BarCodeReader çağrısı için tüm çekirdeklerin kullanılmasını sağlar
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Bu, mevcut çekirdek sayısının kullanılmasını sağlar
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

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



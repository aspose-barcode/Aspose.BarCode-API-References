---
title: "Aspose::BarCode::Common::ProcessorSettings sınıfı"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Common::ProcessorSettings sınıfı. ProcessorSettings, C++'ta çok iş parçacıklı performans artışıyla barkodları tanımayı sağlar."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Kodu paralel olarak çalıştırmak için ek iş parçacıklarının azami sayısını belirtin |
| [get_UseAllCores](./get_useallcores/)() const | Tüm çekirdeklerin kullanılabilmesi için gereklidir. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir. |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Kodu paralel olarak çalıştırmak için ek iş parçacıklarının azami sayısını belirtin |
| [set_UseAllCores](./set_useallcores/)(bool) | Tüm çekirdeklerin kullanılabilmesi için gereklidir. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Kullanılacak çekirdek sayısını belirtin. "UseAllCores" özelliğini "false" olarak değiştirmeniz gerekir. |
## Açıklamalar


Bu örnek, maksimum çok iş parçacıklı performans eklemek için [ProcessorSettings](./) nasıl kullanılacağını gösterir
```cpp
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

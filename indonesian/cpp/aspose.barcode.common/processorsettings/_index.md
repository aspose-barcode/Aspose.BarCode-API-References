---
title: "Aspose::BarCode::Common::ProcessorSettings class"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Common::ProcessorSettings class. ProcessorSettings memungkinkan pengenalan barcode dengan peningkatan kinerja multi‑threaded dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Tentukan jumlah maksimum thread tambahan untuk menjalankan kode secara paralel |
| [get_UseAllCores](./get_useallcores/)() const | Diperlukan untuk menggunakan semua inti. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Tentukan jumlah inti yang akan digunakan. Anda perlu mengubah properti "UseAllCores" menjadi "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Tentukan jumlah maksimum thread tambahan untuk menjalankan kode secara paralel |
| [set_UseAllCores](./set_useallcores/)(bool) | Diperlukan untuk menggunakan semua inti. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Tentukan jumlah inti yang akan digunakan. Anda perlu mengubah properti "UseAllCores" menjadi "false". |
## Catatan


Contoh ini menunjukkan cara menggunakan [ProcessorSettings](./) untuk menambahkan kinerja multi‑threaded maksimum
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//ini memungkinkan penggunaan semua inti untuk satu panggilan BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//ini memungkinkan penggunaan jumlah inti saat ini
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

## Lihat Juga

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::Common::ProcessorSettings class"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Common::ProcessorSettings class. Τα ProcessorSettings επιτρέπουν την αναγνώριση barcode με πολυνηματική βελτίωση της απόδοσης σε C++."
type: docs
weight: 500
url: /el/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα |
| [get_UseAllCores](./get_useallcores/)() const | Απαιτείται για χρήση όλων των πυρήνων. |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | Καθορίστε τον αριθμό πυρήνων προς χρήση. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false". |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα |
| [set_UseAllCores](./set_useallcores/)(bool) | Απαιτείται για χρήση όλων των πυρήνων. |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | Καθορίστε τον αριθμό πυρήνων προς χρήση. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false". |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το [ProcessorSettings](./) για να προσθέσετε τη μέγιστη πολυνηματική απόδοση
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//αυτό επιτρέπει τη χρήση όλων των πυρήνων για μία κλήση BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//αυτό επιτρέπει τη χρήση του τρέχοντος αριθμού πυρήνων
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

## Δείτε επίσης

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

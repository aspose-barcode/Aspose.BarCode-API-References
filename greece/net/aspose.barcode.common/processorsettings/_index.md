---
title: ProcessorSettings
second_title: Aspose.BarCode για Αναφορά API .NET
description: Οι Ρυθμίσεις Επεξεργαστή επιτρέπουν την αναγνώριση γραμμωτών κωδίκων με πολλαπλή αύξηση της απόδοσης
type: docs
weight: 310
url: /el/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

Οι Ρυθμίσεις Επεξεργαστή επιτρέπουν την αναγνώριση γραμμωτών κωδίκων με πολλαπλή αύξηση της απόδοσης

```csharp
public class ProcessorSettings
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για εκτέλεση κώδικα παράλληλα |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Απαιτείται για τη χρήση όλων των πυρήνων. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false". |

### Παραδείγματα

Αυτό το δείγμα δείχνει πώς να χρησιμοποιήσετε τις Ρυθμίσεις Processor για να προσθέσετε μέγιστη απόδοση πολλαπλών νημάτων

```csharp
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

'Αυτό επιτρέπει τη χρήση όλων των πυρήνων για μία κλήση BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = True
'Αυτό επιτρέπει τη χρήση του τρέχοντος αριθμού πυρήνων
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.BarCode.Common](../../aspose.barcode.common/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

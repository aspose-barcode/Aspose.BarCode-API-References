---
title: "Κλάση ProcessorSettings"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Common.ProcessorSettings κλάση. Τα ProcessorSettings επιτρέπουν την αναγνώριση barcode με πολυνηματική αύξηση της απόδοσης"
type: docs
weight: 470
url: /el/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

Το ProcessorSettings επιτρέπει την αναγνώριση barcode με πολυνηματική βελτίωση της απόδοσης.

```csharp
public class ProcessorSettings
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | Καθορίστε τον μέγιστο αριθμό πρόσθετων νημάτων για την εκτέλεση του κώδικα παράλληλα |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | Απαιτείται για τη χρήση όλων των πυρήνων. |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | Καθορίστε τον αριθμό των πυρήνων που θα χρησιμοποιηθούν. Πρέπει να αλλάξετε την ιδιότητα "UseAllCores" σε "false". |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το ProcessorSettings για να προσθέσετε μέγιστη πολυνηματική απόδοση

```csharp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//Αυτό επιτρέπει τη χρήση όλων των πυρήνων για μία κλήση του BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Αυτό επιτρέπει τη χρήση του τρέχοντος αριθμού πυρήνων
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

### Δείτε επίσης

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



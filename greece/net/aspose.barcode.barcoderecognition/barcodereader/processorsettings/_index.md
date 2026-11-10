---
title: "BarCodeReader.ProcessorSettings"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα BarCodeReader. Λαμβάνει τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή"
type: docs
weight: 140
url: /el/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Ανακτά τις ρυθμίσεις χρήσης πυρήνων επεξεργαστή.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το ProcessorSettings για να προσθέσετε μέγιστη πολυνηματική απόδοση

```csharp
[C#]
//Αυτό επιτρέπει τη χρήση όλων των πυρήνων για μία κλήση του BarCodeReader
BarCodeReader.ProcessorSettings.UseAllCores = true;
//Αυτό επιτρέπει τη χρήση του τρέχοντος αριθμού πυρήνων
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Δείτε επίσης

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



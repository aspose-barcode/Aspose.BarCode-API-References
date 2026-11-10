---
title: "BarCodeReader.Timeout"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarCodeReader. Obtient ou définit le délai d'expiration du processus de reconnaissance en millisecondes"
type: docs
weight: 80
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Obtient ou définit le délai d'attente du processus de reconnaissance en millisecondes.

```csharp
public int Timeout { get; set; }
```

### Property Value

Le délai d'attente.

## Exemples

Cet exemple montre comment éviter les blocages de reconnaissance avec le délai d'attente sur les grandes images

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir aussi

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



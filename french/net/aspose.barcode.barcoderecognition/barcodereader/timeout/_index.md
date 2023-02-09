---
title: Timeout
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Obtient ou définit le délai dexpiration du processus de reconnaissance en millisecondes.
type: docs
weight: 70
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

Obtient ou définit le délai d'expiration du processus de reconnaissance en millisecondes.

```csharp
public int Timeout { get; set; }
```

### Valeur de la propriété

Le délai d'attente.

### Exemples

Cet exemple montre comment éviter les blocages de reconnaissance avec timeout sur de grandes images

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

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
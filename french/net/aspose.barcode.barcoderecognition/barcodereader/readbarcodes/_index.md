---
title: "BarCodeReader.ReadBarCodes"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode BarCodeReader. Lit les BarCodeResults de l'image"
type: docs
weight: 110
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader.ReadBarCodes method

Lit les [`BarCodeResult`](../../barcoderesult/)s de l'image.

```csharp
public BarCodeResult[] ReadBarCodes()
```

### Valeur de retour

Renvoie le tableau de [`BarCodeResult`](../../barcoderesult/)s reconnus sur l'image. Si rien n'est reconnu, un tableau vide est renvoyé.

## Exemples

Cet exemple montre comment lire les codes‑barres avec BarCodeReader.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir aussi

* class [BarCodeResult](../../barcoderesult/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



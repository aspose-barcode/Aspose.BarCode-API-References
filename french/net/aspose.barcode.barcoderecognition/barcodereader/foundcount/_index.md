---
title: FoundCount
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Obtient le nombre de codes-barres reconnus
type: docs
weight: 50
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/foundcount/
---
## BarCodeReader.FoundCount property

Obtient le nombre de codes-barres reconnus

```csharp
public int FoundCount { get; }
```

### Valeur de la propriété

Les codes-barres reconnus comptent

### Exemples

Cet exemple montre comment lire des codes-barres avec BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

### Voir également

* class [BarCodeReader](../../barcodereader)
* espace de noms [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* Assemblée [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
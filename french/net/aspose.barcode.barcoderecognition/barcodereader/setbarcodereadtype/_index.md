---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode BarCodeReader. Définit le tableau de type SingleDecodeType pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes"
type: docs
weight: 130
url: /fr/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

Définit le tableau de type [`SingleDecodeType`](../../singledecodetype/) pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes()

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | Le tableau de type [`SingleDecodeType`](../../singledecodetype/) à lire. |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir aussi

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



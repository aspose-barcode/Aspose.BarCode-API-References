---
title: "Énumération BarCodeConfidence"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.BarCodeRecognition.BarCodeConfidence. Contient le niveau de confiance de reconnaissance"
type: docs
weight: 50
url: /fr/net/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enumeration

Contient le niveau de confiance de la reconnaissance

```csharp
public enum BarCodeConfidence
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Confiance de reconnaissance du code-barres lorsque le texte du code n'a pas été reconnu correctement ou que le code-barres a été détecté comme éventuellement faux |
| Moderate | `80` | Confiance de reconnaissance du code-barres (principalement les codes-barres 1D) avec une somme de contrôle faible ou même sans. Peut contenir quelques erreurs de reconnaissance du texte ou même des reconnaissances factices si  est faible. |
| Strong | `100` | Confiance de reconnaissance confirmée par des codes BCH tels que Reed–Solomon. Il ne doit pas y avoir d'erreurs dans le texte lu ou de reconnaissances factices. |

## Exemples

Cet exemple montre comment BarCodeConfidence varie selon le type de code-barres

```csharp
[C#]
//Confiance modérée
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}

//Confiance forte
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



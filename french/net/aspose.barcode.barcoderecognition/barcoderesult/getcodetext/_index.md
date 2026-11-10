---
title: "BarCodeResult.GetCodeText"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "BarCodeResult méthode. Obtient le texte du code avec l'encodage"
type: docs
weight: 130
url: /fr/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Obtient le texte du code avec l'encodage.

```csharp
public string GetCodeText(Encoding encoding)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| encodage | Encodage | L'encodage pour le texte du code. |

### Valeur de retour

Une chaîne contenant le texte du code reconnu.

## Exemples

Cet exemple montre comment utiliser `GetCodeText`:

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Voir aussi

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



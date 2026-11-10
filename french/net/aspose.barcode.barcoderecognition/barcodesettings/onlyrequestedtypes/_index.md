---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété BarcodeSettings. Retourne uniquement les types de codes-barres explicitement spécifiés pour la reconnaissance. Lorsqu’il est activé, les codes-barres reconnus d’autres types compatibles ou équivalents sont filtrés. La valeur par défaut est false"
type: docs
weight: 50
url: /fr/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Renvoie uniquement les types de code-barres explicitement spécifiés pour la reconnaissance. Lorsqu'activé, les codes-barres reconnus d'autres types compatibles ou équivalents sont filtrés. La valeur par défaut est false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Renvoie uniquement les types de code-barres explicitement spécifiés pour la reconnaissance. La valeur par défaut est false.

## Exemples

Cet exemple montre comment restreindre les résultats de reconnaissance aux types de code-barres demandés uniquement

```csharp
[C#]
//générer le code-barres EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//reconnaître uniquement les codes-barres UPCA (aucun résultat, car la source est EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//reconnaître les types compatibles : EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 sera renvoyé comme équivalent UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Voir aussi

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



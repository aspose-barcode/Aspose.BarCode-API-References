---
title: "Enum DeconvolutionMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode enum. Mode de restauration d'image par déconvolution qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée et convoluée par n'importe quelle fonction naturelle comme le flou lors de la capture d'image par une caméra. Comme nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons vérifier les fonctions les mieux connues comme le net ou la morphologie mathématique."
type: docs
weight: 240
url: /fr/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de l'obtention de l'image par la caméra. Parce que nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons vérifier les fonctions les plus connues comme sharp ou mathematical morphology.

```csharp
public enum DeconvolutionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Fast | `0` | Active les méthodes de déconvolution rapides pour les images de haute qualité. |
| Normal | `1` | Active les méthodes de déconvolution normales pour les images courantes. |
| Slow | `2` | Active les méthodes de déconvolution lentes pour les images de faible qualité. |

## Exemples

Cet exemple montre comment utiliser le mode Déconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



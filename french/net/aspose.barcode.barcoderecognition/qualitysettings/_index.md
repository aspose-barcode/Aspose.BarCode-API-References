---
title: "Classe QualitySettings"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.QualitySettings. QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez rapidement configurer QualitySettings avec les préréglages intégrés HighPerformance, NormalQuality, HighQuality, MaxQuality ou bien configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality."
type: docs
weight: 370
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings avec les préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxQuality, ou bien configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality.

```csharp
public sealed class QualitySettings
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | Préréglage de qualité de reconnaissance HighPerformance. Les codes‑barres de haute qualité sont bien reconnus dans ce mode. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | Préréglage de qualité de reconnaissance HighQuality. Ce préréglage est conçu pour les codes‑barres de faible qualité. Il permet de détecter les codes‑barres fortement endommagés. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | Préréglage de qualité de reconnaissance MaxQuality. Ce préréglage est développé pour reconnaître tous les codes‑barres possibles, même les codes‑barres incorrects. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes‑barres |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Permet au moteur de reconnaître les codes‑barres qui ont un checksum incorrect ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes‑barres endommagés avec un texte incorrect. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Mode qui active les méthodes permettant de reconnaître les éléments du code‑à‑barres avec la qualité sélectionnée. Un élément de code‑à‑barres de qualité inférieure nécessite des méthodes plus complexes, ce qui ralentit la reconnaissance. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres couleur sur les images en couleur. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de l'obtention de l'image par la caméra. Parce que nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons vérifier les fonctions les plus connues comme sharp ou mathematical morphology. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres sur des images aux couleurs inversées (luminance). |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | Taille minimale de XDimension en pixels utilisée avec UseMinimalXDimension. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code‑à‑barres : cellule de matrice ou barre. |

## Exemples

Cet exemple montre comment utiliser QualitySettings avec BarCodeReader

```csharp
[C#]
//définir le mode de reconnaissance HighPerformance
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//définir le mode de reconnaissance HighQuality
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//définir le mode de reconnaissance HighPerformance pour les codes-barres de petite taille
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//définir le mode de reconnaissance HighPerformance pour les codes-barres de faible qualité
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



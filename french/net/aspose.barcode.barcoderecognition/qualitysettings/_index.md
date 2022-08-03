---
title: QualitySettings
second_title: Référence de l'API Aspose.BarCode pour .NET
description: QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par des préréglages intégrés  HighPerformance NormalQuality HighQuality MaxBarCodes ou vous pouvez configurer manuellement des options distinctes. La valeur par défaut de QualitySettings est NormalQuality.
type: docs
weight: 250
url: /fr/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par des préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement des options distinctes. La valeur par défaut de QualitySettings est NormalQuality.

```csharp
public sealed class QualitySettings
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | Préréglage de la qualité de reconnaissance HighPerformance. Les codes-barres de haute qualité sont bien reconnus dans ce mode. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Préréglage de qualité de reconnaissance de haute qualité. Ce préréglage est développé pour les codes-barres de faible qualité. Permet de détecter les codes-barres diagonaux et très endommagés. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | Préréglage de qualité de reconnaissance HighQualityDetection. Identique à NormalQuality mais avec une qualité élevée[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | Préréglage de la qualité de reconnaissance MaxBarCodes. Ce préréglage est développé pour reconnaître tous les codes-barres possibles, même les codes-barres incorrects. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | Préréglage de la qualité de reconnaissance MaxQualityDetection. Identique à NormalQuality mais avec la meilleure qualité[`DetectorSettings`](./detectorsettings). Permet de détecter les codes-barres en diagonale et endommagés. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | Préréglage de qualité de reconnaissance NormalQuality. Convient à la plupart des codes-barres |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Permet au moteur de reconnaître les codes-barres de couleur sur fond de couleur en tant que numérisation supplémentaire. Mode extrêmement lent. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Permet au moteur de Datamatrix de reconnaître les codes-barres Datamatrix industriels en pointillés. Mode lent qui n'aide que pour les codes-barres en pointillés constitués de points. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Permet au moteur de reconnaître une image diminuée en tant que numérisation supplémentaire. La taille pour la diminution est sélectionnée par les algorithmes du moteur interne. Le mode aide à reconnaître les codes-barres qui sont bruyants et flous mais capturés avec une haute résolution. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Permet au moteur d'utiliser l'écart entre les scans pour augmenter la vitesse de reconnaissance. Le mode peut poser des problèmes de reconnaissance avec des codes-barres de faible hauteur. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Permet au moteur de reconnaître les codes à barres qui ont une somme de contrôle incorrecte ou des valeurs incorrectes. Le mode peut être utilisé pour reconnaître les codes-barres endommagés avec un texte incorrect. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Permet au moteur de reconnaître l'image couleur inversée en tant que numérisation supplémentaire. Le mode peut être utilisé lorsque le code-barres est blanc sur fond noir. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Permet au moteur d'activer le lissage médian en tant qu'analyse supplémentaire. Le mode aide à reconnaître les codes-barres bruyants. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Permet au moteur pour les codes-barres postaux de reconnaître les images légèrement bruitées. Le mode aide à reconnaître les codes-barres postaux légèrement endommagés. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | Permet au moteur pour les codes-barres 1D de reconnaître rapidement les codes-barres de haute qualité qui remplissent presque toute l'image. Le mode permet de reconnaître rapidement les codes-barres générés à partir d'Internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | Permet au moteur pour les codes-barres 1D de reconnaître les codes-barres avec des barres simples effacées/collées dans le motif. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | Permet au moteur pour QR/MicroQR de reconnaître les codes-barres MicroQR endommagés. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Permet au moteur de reconnaître une image normale sans aucune restauration en tant que numérisation principale. Mode pour reconnaître l'image telle quelle. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Permet au moteur de reconnaître les codes-barres de type sel et bruit de papier. Le mode peut supprimer un petit bruit avec des points blancs et noirs. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Permet au moteur de reconnaître l'image sans petites taches blanches en tant que numérisation supplémentaire. Le mode aide à reconnaître l'image bruitée ainsi que le filtrage de lissage médian. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Permet au moteur de reconnaître les codes-barres 1D avec somme de contrôle en vérifiant plus de variantes de reconnaissance. Valeur par défaut : Faux. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Paramètres du détecteur de code-barres. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | Permet au moteur pour les codes-barres 1D de reconnaître rapidement la tranche médiane d'une image et de renvoyer le résultat sans utiliser d'algorithmes chronophages. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Taille de la fenêtre pour le lissage médian. Les valeurs typiques sont 3 ou 4. La valeur par défaut est 3. AllowMedianSmoothing doit être défini. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Permet au moteur de reconnaître les minuscules codes-barres sur les grandes images. Ignoré si[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) est défini sur Vrai. Valeur par défaut : Faux. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Passe à l'ancien détecteur de code-barres. |

### Exemples

Cet exemple montre comment utiliser QualitySettings avec BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //définit le mode hautes performances
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // le mode de qualité normale est défini par défaut
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //définit le mode haute qualité avec reconnaissance à basse vitesse 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //set max barcodes mode, qui essaie de trouver tous les codes-barres possibles, même incorrects. Le mode de reconnaissance le plus lent
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //définit le mode hautes performances
   reader.QualitySettings = QualitySettings.HighPerformance;
   // définir des options séparées
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // le mode par défaut est NormalQuality
   // définir des options séparées
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'définir le mode hautes performances
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'le mode de qualité normale est défini par défaut
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'définir le mode haute qualité avec reconnaissance à basse vitesse
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'définir le mode codes-barres max, qui essaie de trouver tous les codes-barres possibles, même incorrects. Le mode de reconnaissance le plus lent
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'définir le mode hautes performances
   reader.QualitySettings = QualitySettings.HighPerformance
   'définir des options distinctes
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'le mode par défaut est NormalQuality
   'définir des options distinctes
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Voir également

* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Le Aspose.BarCode.BarCodeRecognition contient des outils pour la reconnaissance des codes‑barres 1D/2D"
type: docs
weight: 20
url: /fr/net/aspose.barcode.barcoderecognition/
---
Le **Aspose.BarCode.BarCodeRecognition** contient des outils pour la reconnaissance des codes-barres 1D/2D.

## Classes

| Classe | Description |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stocke les données spéciales du code‑barres Aztec reconnu |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stocke les paramètres étendus du code‑barres reconnu |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsule une image pouvant contenir un ou plusieurs codes‑barres, puis peut exécuter l'opération ReadBarCodes pour détecter les codes‑barres. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | Exception générale lancée par BarCodeReader, héritée de BarCodeException |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Représente la région du code‑barres reconnu et l'angle du code‑barres |
| [BarCodeResult](./barcoderesult/) | Stocke les données du code‑barres reconnu comme le type [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/), String codetext, la région [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) et d'autres paramètres |
| [BarcodeSettings](./barcodesettings/) | Les principaux paramètres de décodage BarCode. Contient des paramètres qui influencent les données reconnues. |
| [BaseDecodeType](./basedecodetype/) | Classe de base pour MultiDecodeType et SingleDecodeType. |
| [BaseExtendedParameters](./baseextendedparameters/) | Classe de base pour le stockage des paramètres étendus du code‑barres reconnu |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stocke une information supplémentaire Codabar du code‑barres reconnu |
| [Code128DataPortion](./code128dataportion/) | Contient les données du sous‑type pour le code‑barres de type Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stocke les données spéciales du code‑barres Code128 reconnu |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stocke une information supplémentaire DataBar du code‑barres reconnu |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stocke les données spéciales du code‑barres DataMatrix reconnu |
| [DecodeType](./decodetype/) | Spécifiez le type de code‑barres à lire. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stocke les données spéciales du code‑barres DotCode reconnu |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stocke les données spéciales du code‑à‑barres reconnu **GS1 Composite Bar** |
| [Iso15416Quality](./iso15416quality/) | Stocke les notes de qualité du code‑à‑barres calculées selon la norme ISO/IEC 15416 pour les codes‑à‑barres 1D. |
| [IsoSymbolQuality](./isosymbolquality/) | Stocke les résultats d'évaluation de la qualité du symbole du code‑à‑barres selon les normes ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Représente une trame d'image en niveaux de gris de 8 bits. Chaque pixel est représenté par un octet contenant sa valeur de luminance. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stocke des informations supplémentaires MaxiCode du code‑à‑barres reconnu. |
| [MultiDecodeType](./multidecodetype/) | Type de décodage Composite. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stocke les données spéciales du code‑à‑barres 1D reconnu, comme le texte du code séparé et la somme de contrôle. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stocke les métadonnées MacroPdf417 du code‑à‑barres reconnu. |
| [QRExtendedParameters](./qrextendedparameters/) | Stocke les informations d'ajout structuré QR du code‑à‑barres reconnu. |
| [Quadrangle](./quadrangle/) | Stocke un ensemble de quatre Points qui représentent une région de [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/). |
| [QualitySettings](./qualitysettings/) | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings avec les préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxQuality, ou bien configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality. |
| [RecognitionAbortedException](./recognitionabortedexception/) | Représente l'exception d'arrêt de reconnaissance qui est levée lorsqu'un délai d'attente est dépassé pendant la reconnaissance avec BarCodeReader. |
| [SingleDecodeType](./singledecodetype/) | Type de décodage unique. Voir le type de décodage pour obtenir une instance. |
## Interfaces

| Interface | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost. L'implémentation doit être fournie par l'utilisateur. |
## Énumération

| Énumération | Description |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Contient le niveau de confiance de la reconnaissance |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode qui active les méthodes permettant de reconnaître les éléments du code‑à‑barres avec la qualité sélectionnée. Un élément de code‑à‑barres de qualité inférieure nécessite des méthodes plus complexes, ce qui ralentit la reconnaissance. |
| [ChecksumValidation](./checksumvalidation/) | Active la validation de la somme de contrôle pendant la reconnaissance des codes‑à‑barres 1D et postaux. |
| [Code128SubType](./code128subtype/) | Contient les types du sous‑ensemble Code128 |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres couleur sur les images en couleur. |
| [DeconvolutionMode](./deconvolutionmode/) | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction qui peut restaurer une image dégradée (convoluée) par n'importe quelle fonction naturelle comme le flou, lors de l'obtention de l'image par la caméra. Parce que nous ne pouvons pas détecter la fonction d'image qui corrompt l'image, nous devons vérifier les fonctions les plus connues comme sharp ou mathematical morphology. |
| [InverseImageMode](./inverseimagemode/) | Mode qui active ou désactive la reconnaissance supplémentaire des codes‑à‑barres sur des images aux couleurs inversées (luminance). |
| [XDimensionMode](./xdimensionmode/) | Mode de reconnaissance qui définit la taille (de 1 à l'infini) de l'élément minimal du code‑à‑barres : cellule de matrice ou barre. |



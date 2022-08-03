---
title: Aspose.BarCode.Generation
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Le Aspose.BarCode.Generation contenant des classes générales pour limplémentation des fonctions de génération de BarCode.
type: docs
weight: 50
url: /fr/net/aspose.barcode.generation/
---
Le **Aspose.BarCode.Generation** contenant des classes générales pour l'implémentation des fonctions de génération de BarCode.

## Des classes

| Classer | La description |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | Paramètres de code-barres AustralianPost. |
| [AztecParameters](./aztecparameters) | Paramètres aztèques. |
| [BarcodeGenerator](./barcodegenerator) | BarcodeGenerator pour la génération d'images de codes à barres backend. |
| [BarcodeParameters](./barcodeparameters) | Paramètres de génération de code-barres. |
| [BaseEncodeType](./baseencodetype) | Classe de base pour SymbologyEncodeType. |
| [BaseGenerationParameters](./basegenerationparameters) | Paramètres de génération d'image de code-barres. |
| [BorderParameters](./borderparameters) | Paramètres de bordure d'image de code-barres |
| [CaptionParameters](./captionparameters) | Paramètres de légende. |
| [CodabarParameters](./codabarparameters) | Paramètres Codabar. |
| [CodablockParameters](./codablockparameters) | Paramètres Codablock. |
| [Code16KParameters](./code16kparameters) | Paramètres Code16K. |
| [CodetextParameters](./codetextparameters) | Paramètres de texte de code. |
| [CouponParameters](./couponparameters) | Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarParameters](./databarparameters) | Paramètres de la barre de données. |
| [DataMatrixParameters](./datamatrixparameters) | Paramètres DataMatrix. |
| [DotCodeParameters](./dotcodeparameters) | Paramètres DotCode. |
| [EncodeTypes](./encodetypes) | Spécifie le type de code-barres à encoder. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Classe d'assistance pour la génération automatique de texte de code du mode de texte de code étendu |
| [FontUnit](./fontunit) | Définit un format particulier pour le texte, y compris le type de police, la taille et les attributs de style où taille dans la propriété de valeur d'unité. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | Paramètres de la barre composite GS1. |
| [ITFParameters](./itfparameters) | Paramètres ITF. |
| [MaxiCodeParameters](./maxicodeparameters) | Paramètres MaxiCode. |
| [Padding](./padding) | Paramètres de rembourrage. |
| [PatchCodeParameters](./patchcodeparameters) | Paramètres PatchCode. |
| [Pdf417Parameters](./pdf417parameters) | Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417 et MicroPDF417. MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs. MicroPDF417 en mode d'ajout structuré (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs. |
| [PostalParameters](./postalparameters) | Paramètres postaux. Utilisé pour Postnet, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | Générateur de texte de code étendu pour les codes-barres QR 2D pour le mode ExtendedCodetext de QrEncodeMode |
| [QrParameters](./qrparameters) | Paramètres QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | Paramètres d'ajout structuré QR. |
| [SupplementParameters](./supplementparameters) | Paramètres supplémentaires. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SymbologyEncodeType](./symbologyencodetype) | Type d'encodage de symbologie. Voir EncodeTypes pour obtenir l'instance. |
| [Unit](./unit) | Spécifie la valeur de taille dans différentes unités (pixel, pouces, etc.). |
## Énumération

| Énumération | La description |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Spécifie les différents types de modes de dimensionnement automatique. |
| [AztecSymbolMode](./aztecsymbolmode) | Spécifie le mode symbole aztèque. |
| [BarcodeClassifications](./barcodeclassifications) | Classification de la symbologie |
| [BarCodeImageFormat](./barcodeimageformat) | Spécifie le format de fichier de l'image. |
| [BorderDashStyle](./borderdashstyle) | Spécifie le style des bordures en pointillés. |
| [CodabarChecksumMode](./codabarchecksummode) | Spécifie l'algorithme de somme de contrôle pour Codabar |
| [CodabarSymbol](./codabarsymbol) | Spécifie le symbole de début ou de fin de la spécification de code à barres Codabar. |
| [Code128Emulation](./code128emulation) | Mots de code de fonction pour l'émulation Code 128. Appliqué pour MicroPDF417 uniquement. Ignoré pour les codes-barres PDF417 et MacroPDF417. |
| [CodeLocation](./codelocation) | Emplacement du texte de code |
| [DataMatrixEccType](./datamatrixecctype) | Spécifiez le type d'ECC à encoder. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | Mode d'encodage de l'encodeur DataMatrix, par défaut Auto |
| [ECIEncodings](./eciencodings) | Identificateurs d'interprétation de canal étendu. Il est utilisé pour indiquer au lecteur de code-barres les détails des références utilisées pour coder les données dans le symbole. L'implémentation actuelle comprend tous les codages de jeu de caractères bien connus. Actuellement, il est utilisé uniquement pour le code-barres QR 2D. |
| [EnableChecksum](./enablechecksum) | Activer la somme de contrôle lors de la génération pour les codes-barres 1D. |
| [FontMode](./fontmode) | Mode taille de police. |
| [ITF14BorderType](./itf14bordertype) | Type de bordure ITF14 du code-barres |
| [MacroCharacter](./macrocharacter) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un codage plus compact dans des modes spéciaux. 05 Le caractère macro est traduit par "[)&gt;\u001E05\u001D" comme en-tête de données décodées et "\u001E\u0004" comme fin de données décodées. 06 Le caractère de macro est traduit en "[)&gt;\u001E06\u001D" comme en-tête de données décodées et "\u001E\u0004" comme fin de données décodée. |
| [PatchFormat](./patchformat) | Format PatchCode. Choisissez PatchOnly pour générer un seul PatchCode. Utilisez le format de page pour générer la page Patch avec PatchCodes comme border |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 mode compactage code barre |
| [Pdf417ErrorLevel](./pdf417errorlevel) | Niveau de correction d'erreur du code-barres pdf417, du niveau 0 au niveau 9, le niveau 0 signifie aucune correction d'erreur, le niveau 9 signifie la meilleure correction d'erreur |
| [QREncodeMode](./qrencodemode) | Mode d'encodage pour les codes-barres QR. Il est recommandé d'utiliser Auto avec CodeTextEncoding = Encoding.UTF8 pour les symboles ou chiffres latins et Utf8BOM pour les symboles Unicode. |
| [QREncodeType](./qrencodetype) | Mode sélecteur QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standard, Auto pour MicroQR. ForceMicroQR est utilisé pour la génération de symboles fortement MicroQR si cela est possible. |
| [QRErrorLevel](./qrerrorlevel) | Niveau de correction d'erreur Reed-Solomon. De bas en haut : NiveauL, NiveauM, NiveauQ, NiveauH. |
| [QRVersion](./qrversion) | Version du QR Code. De la Version1 à la Version40 pour le QR code et de M1 à M4 pour le MicroQr. |
| [TextAlignment](./textalignment) | Alignement du texte. |
| [TwoDComponentType](./twodcomponenttype) | Type de composant 2D |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

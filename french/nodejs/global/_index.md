---
title: "Global"
linktitle: "Global"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "L'espace de noms Global regroupe les énumérations de base et les classes utilitaires utilisées dans Aspose.BarCode pour Node.js via Java."
type: docs
weight: 20
url: /fr/nodejs/global/
---
L'espace de noms Global fournit une collection d'énumérations fondamentales et de types d'assistance qui définissent les propriétés des codes-barres telles que les modes d'encodage, les tailles de symbole, les niveaux de confiance et les formats d'image. Ces définitions sont référencées tout au long de l'API Aspose.BarCode pour configurer et interpréter la génération et la reconnaissance des codes-barres.

## Énumérations

| Énumération | Description |
| --- | --- |
| [AddressType](./addresstype/) | Type d'adresse |
| [AutoSizeMode](./autosizemode/) | Spécifie les différents types de modes de dimensionnement automatique. La valeur par défaut est AutoSizeMode.NONE. |
| [AztecEncodeMode](./aztecencodemode/) | Mode d'encodage pour les codes-barres Aztec. |
| [AztecSymbolMode](./aztecsymbolmode/) | Spécifie le mode du symbole Aztec. |
| [BarCodeConfidence](./barcodeconfidence/) | Contient le niveau de confiance de reconnaissance |
| [BarCodeImageFormat](./barcodeimageformat/) | Spécifie le format de fichier de l'image. |
| [BarcodeClassifications](./barcodeclassifications/) | BarcodeClassifications EncodeTypes classification |
| [BarcodeQualityMode](./barcodequalitymode/) | Mode qui permet aux méthodes de reconnaître les éléments de code-barres avec la qualité sélectionnée. Élément de code-barres de qualité inférieure r |
| [BorderDashStyle](./borderdashstyle/) | Spécifie le style des lignes de bordure en pointillés. |
| [ChecksumValidation](./checksumvalidation/) | Active la validation du checksum pendant la reconnaissance des codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent cont |
| [CodabarChecksumMode](./codabarchecksummode/) | Spécifie l'algorithme de checksum pour Codabar |
| [CodabarSymbol](./codabarsymbol/) | Spécifie le symbole de début ou de fin de la spécification du code-barres Codabar. |
| [Code128EncodeMode](./code128encodemode/) | Mode d'encodage pour les codes-barres Code128. `Code  128` spécification. Ce code montre comment générer le code 128 avec diffe |
| [Code128SubType](./code128subtype/) | Contient les types du sous-ensemble Code128 |
| [CodeLocation](./codelocation/) | Emplacement du texte du code |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres couleur sur des images couleur. Cet exemple montre comment utiliser Co |
| [CustomerInformationInterpretingType](./customerinformationinterpretingtype/) | Définit le type d'interprétation (C_TABLE ou N_TABLE) des informations client pour le code-barres AustralianPost. |
| [DataMatrixEccType](./datamatrixecctype/) | Spécifiez le type de ECC à encoder. |
| [DataMatrixEncodeMode](./datamatrixencodemode/) | Mode d'encodage de l'encodeur DataMatrix, par défaut sur Auto. Cet exemple montre comment faire du texte de code en Mode Étendu. //Auto mode l |
| [DataMatrixVersion](./datamatrixversion/) | Spécifiez le type de ECC à encoder. |
| [DecodeType](./decodetype/) | Spécifiez le type de code-barres à lire. |
| [DeconvolutionMode](./deconvolutionmode/) | Mode de déconvolution (restauration d'image) qui définit le niveau de dégradation de l'image. À l'origine, la déconvolution est une fonction |
| [DotCodeEncodeMode](./dotcodeencodemode/) | Mode d'encodage pour les codes-barres DotCode. |
| [ECIEncodings](./eciencodings/) | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [EnableChecksum](./enablechecksum/) | Activez la somme de contrôle lors de la génération pour les codes-barres 1D. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir une somme de contrôle |
| [EncodeTypes](./encodetypes/) | Spécifie le type de code-barres à encoder. |
| [FontMode](./fontmode/) | Mode de taille de police. |
| [FontStyle](./fontstyle/) | Classification FontStyle |
| [GraphicsUnit](./graphicsunit/) | Spécifie l'unité de mesure pour les données données. |
| [HIBCLICDateFormat](./hibclicdateformat/) | Spécifie les différents types de formats de date pour HIBC LIC. |
| [HIBCPASDataLocation](./hibcpasdatalocation/) | Types d'emplacement des données HIBC PAS. |
| [HIBCPASDataType](./hibcpasdatatype/) | Types de données des enregistrements HIBC PAS. |
| [HanXinEncodeMode](./hanxinencodemode/) | Mode d'encodage Han Xin Code. Il est recommandé d'utiliser Auto avec les caractères ASCII / chinois ou Unicode pour les caractères Unicode |
| [HanXinErrorLevel](./hanxinerrorlevel/) | Niveau de correction d'erreur Reed-Solomon. Du plus bas au plus haut : L1, L2, L3, L4. |
| [HanXinVersion](./hanxinversion/) | Version du Han Xin Code. De Version01 - 23 x 23 modules à Version84 - 189 x 189 modules, augmentant par pas de 2 modules |
| [ITF14BorderType](./itf14bordertype/) | Type de bordure du code-barres ITF14 |
| [InverseImageMode](./inverseimagemode/) | Mode qui active ou désactive la reconnaissance supplémentaire des codes-barres sur des images avec des couleurs inversées (luminance). Cet exemple |
| [MacroCharacter](./macrocharacter/) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Le caractère macro 05 est trans |
| [Mailmark2DType](./mailmark2dtype/) | Le type Mailmark 2D définit la taille du code-barres Data Matrix |
| [MaxiCodeEncodeMode](./maxicodeencodemode/) | Mode d'encodage pour les codes-barres MaxiCode. |
| [MaxiCodeMode](./maxicodemode/) | Mode d'encodage pour les codes-barres MaxiCode. |
| [MicroQRVersion](./microqrversion/) | Version du MicroQR Code. De M1 à M4. |
| [PatchFormat](./patchformat/) | Format PatchCode. Choisissez PatchOnly pour générer un seul PatchCode. Utilisez le format page pour générer une page Patch avec des PatchCodes |
| [Pdf417CompactionMode](./pdf417compactionmode/) | Mode de compression du code-barres Pdf417 |
| [Pdf417EncodeMode](./pdf417encodemode/) | Mode d'encodage du code-barres Pdf417 |
| [Pdf417ErrorLevel](./pdf417errorlevel/) | Niveau de correction d'erreurs du code-barres pdf417, de 0 à 9, le niveau 0 signifie aucune correction d'erreurs, le niveau 9 signifie le meilleur. |
| [Pdf417MacroTerminator](./pdf417macroterminator/) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PD. |
| [QREncodeMode](./qrencodemode/) | Mode d'encodage pour les codes QR. Exemple d'utilisation de l'encodage ECI : generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TE |
| [QREncodeType](./qrencodetype/) | Mode de sélection QR / MicroQR. Sélectionnez FORCE_QR pour les symboles QR standards, AUTO pour MicroQR. FORCE_MICRO_QR est utilisé pour les cas forts. |
| [QRErrorLevel](./qrerrorlevel/) | Niveau de correction d'erreurs Reed-Solomon. Du plus bas au plus haut : LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. |
| [QRVersion](./qrversion/) | Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. |
| [QrBillStandardVersion](./qrbillstandardversion/) | Version standard du billet SwissQR |
| [QrExtCompactionMode](./qrextcompactionmode/) | Spécifie le mode de compaction QR pour le texte de code ajouté par QrExtCodetextBuilder. |
| [RectMicroQRVersion](./rectmicroqrversion/) | Version du code RectMicroQR. De la version R7x43 à la version R17x139. |
| [SvgColorMode](./svgcolormode/) | Modes possibles pour le remplissage de couleur dans un fichier svg, RGB est le défaut et pris en charge par SVG 1.1. RGBA, HSL, HSLA sont autorisés dans SVG. |
| [TextAlignment](./textalignment/) | Alignement du texte. |

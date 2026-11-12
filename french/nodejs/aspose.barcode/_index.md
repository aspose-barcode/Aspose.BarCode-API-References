---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "L'espace de noms aspose.barcode propose des classes et des énumérations pour créer, personnaliser et décoder une grande variété de types de codes-barres dans Node.js via Java."
type: docs
weight: 10
url: /fr/nodejs/aspose.barcode/
---
Utilisez ces types pour configurer les paramètres de génération de codes-barres tels que le format d'adresse, les spécifications régionales et les paramètres avancés pour Aztec et d'autres symbologies. L'espace de noms comprend des assistants pour créer des textes de code étendus et gérer les normes postales spécialisées.

## Classes

| Classe | Description |
| --- | --- |
| [Address](./address/) | Adresse du créancier ou du débiteur. Vous pouvez soit définir la rue, le numéro, le code postal et la ville (type adresse structurée) o |
| [AlternativeScheme](./alternativescheme/) | Instructions du schéma de paiement alternatif |
| [AustraliaPostSettings](./australiapostsettings/) | Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost |
| [AustralianPostParameters](./australianpostparameters/) | Paramètres du code-barres AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Générateur de texte de code étendu pour les codes-barres Aztec en mode ExtendedCodetext d'AztecEncodeMode. Utilisez la propriété TwoDDisplayText. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Stocke les données spéciales du code-barres Aztec reconnu. Cet exemple montre comment obtenir les valeurs brutes Aztec : let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Paramètres Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Stocke les paramètres étendus du code-barres reconnu |
| [BarCodeReader](./barcodereader/) | BarCodeReader encapsule une image qui peut contenir un ou plusieurs codes-barres, puis peut exécuter l'opération ReadBarCodes |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Représente la région du code-barres reconnu et l'angle du code-barres |
| [BarCodeResult](./barcoderesult/) | Stocke les données du code-barres reconnu comme le type SingleDecodeType, le texte de code `string`, la région BarCodeRegionParameters et d'autres p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator pour la génération d'images de codes-barres côté serveur. symbologies prises en charge : 1D : Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Paramètres de génération de code-barres. |
| [BarcodeSettings](./barcodesettings/) | Les principaux paramètres de décodage du BarCode. Contient des paramètres qui influencent les données reconnues. |
| [BaseGenerationParameters](./basegenerationparameters/) | Paramètres de génération d'image de code-barres. |
| [BorderParameters](./borderparameters/) | Paramètres de bordure d'image de code-barres |
| [CMYKColor](./cmykcolor/) | Classe pour la couleur CMYK. Une instance nulle signifie que le CMYK n'est pas utilisé, et que la couleur RGB par défaut est utilisée. |
| [CaptionParameters](./captionparameters/) | Paramètres de légende. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Stocke des informations supplémentaires Codabar du code-barres reconnu |
| [CodabarParameters](./codabarparameters/) | Paramètres Codabar. |
| [CodablockParameters](./codablockparameters/) | Paramètres Codablock. |
| [Code128DataPortion](./code128dataportion/) | Contient les données du sous-type pour le code-barres de type Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Stocke des données spéciales du code-barres Code128 reconnu. Représente la région du code-barres reconnu et l'angle du code-barres |
| [Code128Parameters](./code128parameters/) | Paramètres Code128. |
| [Code16KParameters](./code16kparameters/) | Paramètres Code16K. |
| [CodetextParameters](./codetextparameters/) | Paramètres Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator pour la génération d'images de code-barres complexes côté serveur (p. ex. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader décode le codetext en type de code-barres complexe spécifié. |
| [CouponParameters](./couponparameters/) | Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Stocke des informations supplémentaires DataBar du code-barres reconnu |
| [DataBarParameters](./databarparameters/) | Paramètres Databar. |
| [DataElement](./dataelement/) | Représente un champ de données spécifique à une juridiction utilisé dans les documents, par exemple ElementID = "ZVA" avec Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Générateur de codetext étendu pour les codes-barres 2D DataMatrix en mode ExtendedCodetext de DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Stocke des données spéciales du code-barres DataMatrix reconnu. Cet exemple montre comment obtenir les valeurs brutes de DataMatrix, laissez le générateur = |
| [DataMatrixParameters](./datamatrixparameters/) | Paramètres DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Générateur de codetext étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext de DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Stocke des données spéciales du code-barres DotCode reconnu. Cet exemple montre comment obtenir les valeurs brutes de DotCode |
| [DotCodeParameters](./dotcodeparameters/) | Paramètres DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Classe d'assistance pour la génération automatique de codetext du mode texte de code étendu |
| [FontUnit](./fontunit/) | Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style où la taille se trouve dans la propriété de valeur Unit. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Stocke les données spéciales du code‑barres reconnu `GS1 Composite Bar` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Paramètres du code‑barres composite GS1. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires et secondaires. Cet exemple |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code HIBC LIC. Cet exemple montre comment décoder le HIBC LI brut |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données primaires. Cet exemple montre comment |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC LIC qui stocke les données secondaires. |
| [HIBCPASCodetext](./hibcpascodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Classe pour le stockage de l'enregistrement HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Générateur de texte de code étendu pour le code Han Xin en mode étendu de HanXinEncodeMode //mode texte de code étendu //créer cod |
| [HanXinParameters](./hanxinparameters/) | Paramètres Han Xin. |
| [HslaColor](./hslacolor/) | Classe représentant la couleur HSLA (Teinte, Saturation, Luminosité, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Interface pour le texte de code complexe utilisé avec ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | Paramètres ITF. |
| [ImageParameters](./imageparameters/) | Paramètres d'image. |
| [License](./license/) | Fournit des méthodes pour licencier le composant. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états. |
| [MandatoryFields](./mandatoryfields/) | Éléments obligatoires (champs) de la carte |
| [MaxiCodeCodetext](./maxicodecodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode. Cet exemple montre comment décoder le MaxiCod brut |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour le mode 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Classe pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour le mode 3. Cet exemple montre comment encoder et |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Générateur de texte de code étendu pour les codes‑barres MaxiCode en mode ExtendedCodetext de MaxiCodeEncodeMode Utilisez TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Stocke une information supplémentaire MaxiCode du code-barres reconnu |
| [MaxiCodeParameters](./maxicodeparameters/) | Paramètres MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Classe pour l'encodage et le décodage du texte codé MaxiCode pour les modes 4, 5 et 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Classe pour l'encodage et le décodage du texte codé MaxiCode pour les modes 4, 5 et 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Classe pour l'encodage et le décodage du deuxième message standard pour le code-barres MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Classe pour l'encodage et le décodage du deuxième message standard pour le code-barres MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Classe pour l'encodage et le décodage du deuxième message structuré pour le code-barres MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Stocke des données spéciales du code-barres 1D reconnu, comme le texte codé séparé et la somme de contrôle |
| [OptionalFields](./optionalfields/) | Éléments optionnels (champs) de la carte |
| [Padding](./padding/) | Paramètres de remplissage. |
| [PatchCodeParameters](./patchcodeparameters/) | Paramètres PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Stocke une information de métadonnées MacroPdf417 du code-barres reconnu |
| [Pdf417Parameters](./pdf417parameters/) | Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417. MacroPDF417 nécessite deux fie |
| [PdfParameters](./pdfparameters/) | Enveloppe des paramètres PDF. Attend une instance sous‑jacente `mwObject` qui fournit les méthodes d'accès (getter/setter) correspondantes |
| [PostalParameters](./postalparameters/) | Paramètres postaux. Utilisé pour Postnet, Planet. |
| [PrimaryData](./primarydata/) | Classe pour stocker les données principales HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | Stocke une information QR Structured Append du code-barres reconnu |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Générateur de texte codé étendu pour les codes QR 2D en mode ExtendedCodetext de QREncodeMode. Utilisez la propriété Display2DText de B |
| [QrParameters](./qrparameters/) | Paramètres QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | Paramètres QR Structured Append. |
| [Quadrangle](./quadrangle/) | Stocke un ensemble de quatre Points qui représentent une région quadrilatère. |
| [QualitySettings](./qualitysettings/) | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Représente l'exception d'annulation de reconnaissance qui est levée lorsqu'un délai d'attente est dépassé pendant la reconnaissance avec BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Classe pour stocker les données secondaires et supplémentaires HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | Les propriétés du sous‑fichier USA DL, le décalage et la longueur sont définis automatiquement. |
| [SupplementParameters](./supplementparameters/) | Paramètres de supplément. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | Paramètres SVG. |
| [SwissQRBill](./swissqrbill/) | Données de facture SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Classe pour l'encodage et le décodage du texte intégré dans le code PDF417 du permis de conduire américain. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Classe pour les champs spécifiques à la juridiction pour le permis de conduire américain (USA DL). |
| [Unit](./unit/) | Spécifie la valeur de taille dans différentes unités (Pixel, Inches, etc). |

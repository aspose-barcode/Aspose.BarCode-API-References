---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Ce package contient des outils pour la reconnaissance de codes-barres 1D/2D."
type: docs
weight: 12
url: /fr/java/com.aspose.barcode.barcoderecognition/
---

Ce package contient des outils pour la reconnaissance de codes-barres 1D/2D.


## Classes

| Classe | Description |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Paramètres de décodage AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Stocke les données spéciales du code-barres Aztec reconnu |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Stocke les paramètres étendus du code-barres reconnu |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader encapsule une image pouvant contenir un ou plusieurs codes-barres, puis peut exécuter l'opération ReadBarCodes pour détecter les codes-barres. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Exception générale lancée par BarCodeReader, héritée de BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Représente la région du code-barres reconnu et l'angle du code-barres |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Stocke les données du code-barres reconnu telles que le type SingleDecodeType, la chaîne codetext, les paramètres BarCodeRegionParameters de la région et d'autres paramètres |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Les principaux paramètres de décodage du code-barres. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Paramètres du détecteur de code-barres. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Classe de base pour MultiDecodeType et SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Classe de base pour le stockage des paramètres étendus du code-barres reconnu |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Stocke une information supplémentaire Codabar du code‑barres reconnu |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Contient les données du sous‑type du code‑barres de type Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Stocke des données spéciales du code‑barres Code128 reconnu |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Stocke des informations supplémentaires DataBar du code‑barres reconnu BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Stocke des données spéciales du code‑barres DataMatrix reconnu |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Spécifiez le type de code‑barres à lire. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Stocke des données spéciales du code‑barres DotCode reconnu |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Stocke des données spéciales du **GS1 Composite Bar** du code‑barres reconnu |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Stocke des informations supplémentaires MaxiCode du code‑barres reconnu |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Type de décodage composite. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Stocke des données spéciales du code‑barres 1D reconnu comme le codetext séparé et la somme de contrôle |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Stocke des informations de métadonnées MacroPdf417 du code‑barres reconnu |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings permet de reconnaître les code‑barres avec une amélioration des performances multithread |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Stocke des informations QR Structured Append du code‑barres reconnu |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Stocke un ensemble de quatre Points qui représentent une région Quadrangle. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Représente l'exception d'annulation de reconnaissance qui est levée en cas de dépassement du délai d'attente pendant la reconnaissance avec BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Type de décodage simple. |

## Interfaces

| Interface | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Interface publique pour le décodage du champ d'information client utilisé dans la symbologie AustraliaPost. |

## Énumérations

| Enum | Description |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Contient le niveau de confiance de la reconnaissance |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contient les types du sous‑ensemble Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Définit le type d'interprétation (C\_TABLE ou N\_TABLE) des informations client pour le code-barres AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

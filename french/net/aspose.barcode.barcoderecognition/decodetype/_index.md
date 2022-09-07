---
title: DecodeType
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Spécifiez le type de code-barres à lire.
type: docs
weight: 190
url: /fr/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Spécifiez le type de code-barres à lire.

```csharp
public static class DecodeType
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray) { get; } | Obtient un tableau qui représente AllSupportedTypes |

## Méthodes

| Nom | La description |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames)() | Récupère un tableau des noms des types de décodage. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d)(BaseDecodeType) | Détermine si le spécifié[`BaseDecodeType`](../basedecodetype) contient toute symbologie de code-barres 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d)(BaseDecodeType) | Détermine si le spécifié[`BaseDecodeType`](../basedecodetype) contient toute symbologie de code-barres 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal)(BaseDecodeType) | Détermine si le spécifié[`BaseDecodeType`](../basedecodetype) contient toute symbologie de code-barres postal |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse)(string, out SingleDecodeType) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets)(params BaseDecodeType[]) | Spécifier les scan sets par barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse)(string, out MultyDecodeType) | Convertit la représentation sous forme de chaîne d'un MultyDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse#tryparse_1)(string, out SingleDecodeType) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |

## Des champs

| Nom | La description |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes) | Spécifie que les données seront vérifiées avec toutes les symbologies disponibles |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel) | Spécifie que les données doivent être décodées avec **Code à barres eParcel domestique de la poste australienne** spécification de code à barres |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost) | Spécifie que les données doivent être décodées avec **Poste australienne** spécification de code-barres |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec) | Spécifie que les données doivent être décodées avec **Aztèque** spécification de code-barres |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar) | Spécifie que les données doivent être décodées avec **Codabar** spécification de code à barres |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf) | Spécifie que les données doivent être décodées avec **CodablockF** spécification de code-barres |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11) | Spécifie que les données doivent être décodées avec **CODES 11** spécification de code à barres |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128) | Spécifie que les données doivent être décodées avec **CODES 128** spécification de code à barres |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k) | Spécifie que les données doivent être décodées avec **SCode16K** spécification de code-barres |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32) | Spécifie que les données doivent être décodées avec **Code32** spécification vierge |
| static readonly [Code39Extended](../../aspose.barcode.barcoderecognition/decodetype/code39extended) | Spécifie que les données doivent être décodées avec **CODE 39 étendu** spécification de code à barres |
| static readonly [Code39Standard](../../aspose.barcode.barcoderecognition/decodetype/code39standard) | Spécifie que les données doivent être décodées avec **Norme CODE 39** spécification de code à barres |
| static readonly [Code93Extended](../../aspose.barcode.barcoderecognition/decodetype/code93extended) | Spécifie que les données doivent être décodées avec **CODE 93 étendu** spécification de code à barres |
| static readonly [Code93Standard](../../aspose.barcode.barcoderecognition/decodetype/code93standard) | Spécifie que les données doivent être décodées avec **Norme CODE 93** spécification de code à barres |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417) | Spécifie que les données doivent être décodées avec **CompactPdf417** (Pdf417Tronqué) spécification de code à barres |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded) | Spécifie que les données doivent être décodées avec **Barre de données GS1 étendue** spécification de code-barres |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked) | Spécifie que les données doivent être décodées avec **GS1 Databar étendu empilé** spécification de code-barres |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited) | Spécifie que les données doivent être décodées avec **Barre de données GS1 limitée** spécification de code-barres |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional) | Spécifie que les données doivent être décodées avec **GS1 Databar omnidirectionnelle** spécification de code-barres |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked) | Spécifie que les données doivent être décodées avec **Barre de données GS1 empilée** spécification de code-barres |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional) | Spécifie que les données doivent être décodées avec **GS1 Databar empilé omnidirectionnel** spécification de code-barres |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated) | Spécifie que les données doivent être décodées avec **Barre de données GS1 tronquée** spécification de code-barres |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5) | Spécifie que les données doivent être décodées avec **DataLogic 2 sur 5** spécification vierge |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix) | Spécifie que les données doivent être décodées avec **Matrice de données** symbologie de code-barres |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode) | Spécifie que les données doivent être décodées avec **Code d'identification Deutsche Post** spécification de code à barres |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode) | Spécifie que les données doivent être décodées avec **Code DeutschePost Leit** spécification de code à barres |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode) | Spécifie que les données doivent être décodées avec **Code de point** spécification vierge |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix) | Spécifie que les données doivent être décodées avec **Code de point** spécification vierge |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13) | Spécifie que les données doivent être décodées avec **EAN-13** spécification de code à barres |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14) | Spécifie que les données doivent être décodées avec **EAN14** spécification de code-barres |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8) | Spécifie que les données doivent être décodées avec **EAN-8** spécification de code à barres |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128) | Spécifie que les données doivent être décodées avec **CODE GS1 128** spécification de code à barres |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix) | Spécifie que les données doivent être décodées avec **GS1DataMatrix** symbologie de code-barres |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr) | Spécifie que les données doivent être décodées avec **QR GS1** spécification de code-barres |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5) | Spécifie que les données doivent être décodées avec **IATA 2 sur 5** spécification du code-barres. L'IATA (International Air Transport Association) utilise ce code-barres pour la gestion du fret aérien. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5) | Spécifie que les données doivent être décodées avec **ENTRELACÉ 2 sur 5** spécification de code à barres |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn) | Spécifie que les données doivent être décodées avec **ISBN** spécification de code à barres |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn) | Spécifie que les données doivent être décodées avec **ISMN** spécification de code à barres |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn) | Spécifie que les données doivent être décodées avec **ISSN** spécification de code à barres |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25) | Spécifie que les données doivent être décodées avec **Poste italienne 25** spécification de code à barres |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14) | Spécifie que les données doivent être décodées avec **ITF14** spécification de code-barres |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6) | Spécifie que les données doivent être décodées avec **ITF6** spécification de code à barres |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417) | Spécifie que les données doivent être décodées avec **MacroPdf417** spécification de code-barres |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark) | Spécifie que les données doivent être décodées avec **Marque postale Royal Mail** spécification de code-barres. |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5) | Spécifie que les données doivent être décodées avec **Matrice 2 sur 5** spécification de code à barres |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode) | Spécifie que les données doivent être décodées avec **MaxiCode** spécification de code-barres |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b) | Spécifie que les données doivent être décodées avec **MICR E-13B** spécification vierge |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417) | Spécifie que les données doivent être décodées avec **MicroPdf417** spécification de code-barres |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr) | Spécifie que les données doivent être décodées avec **Code microQR** spécification de code-barres |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes) | Spécifie que les données seront vérifiées avec les symbologies les plus couramment utilisées |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi) | Spécifie que les données doivent être décodées avec **MSI Plessey** spécification de code à barres |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none) | Type de décodage non spécifié. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode) | Spécifie que les données doivent être décodées avec USPS **UnCode** spécification de code-barres |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc) | Spécifie que les données doivent être décodées avec **OPC** spécification de code à barres |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode) | Spécifie que les données doivent être décodées avec **Code correctif** spécification du code-barres. La symbologie des codes-barres est utilisée pour la numérisation automatisée |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417) | Spécifie que les données doivent être décodées avec **Pdf417** symbologie de code-barres |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode) | Spécifie que les données doivent être décodées avec **Pharmacode** code à barre. Cette symbologie est également connue sous le nom de Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet) | Spécifie que les données doivent être décodées avec **Planète** spécification de code-barres |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes) | Spécifie que les données seront vérifiées avec tous **Poste 1.5D** symbologies de code-barres, comme **Planète, Postnet, AustraliaPost, OneCode, RM4SCC, DutchKIX** |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet) | Spécifie que les données doivent être décodées avec **Postnet** spécification de code à barres |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn) | Spécifie que les données doivent être décodées avec **PZN**spécification du code-barres. Cette symbologie est également connue sous le nom de Pharma Zentral Nummer |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr) | Spécifie que les données doivent être décodées avec **QR Code** spécification de code-barres |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc) | Spécifie que les données doivent être décodées avec **RM4SCC** spécification du code-barres. RM4SCC (Royal Mail 4-state Customer Code) est utilisé pour le processus de tri automatisé du courrier au Royaume-Uni. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14) | Spécifie que les données doivent être décodées avec **CCS14** spécification de code-barres |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18) | Spécifie que les données doivent être décodées avec **SSCC18** spécification de code-barres |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5) | Spécifie que les données doivent être décodées avec **Norme 2 sur 5** spécification de code à barres |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement) | Spécifie que les données doivent être décodées avec **Supplément (EAN2, EAN5)** spécification de code à barres |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel) | Spécifie que les données doivent être décodées avec **Code-barres du colis de la Poste Suisse** spécification de code-barres |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d) | Spécifie que les données seront vérifiées avec tous **1D** symbologies de codes-barres |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d) | Spécifie que les données seront vérifiées avec tous **2D** symbologies de codes-barres |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca) | Spécifie que les données doivent être décodées avec **CUP-A** spécification de code à barres |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce) | Spécifie que les données doivent être décodées avec **CUP-E** spécification de code à barres |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin) | Spécifie que les données doivent être décodées avec **NIV** (Numéro d'identification du véhicule) spécification de code à barres |

### Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir également

* espace de noms [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

---
title: "Classe DecodeType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.DecodeType classe. Spécifiez le type de code-barres à lire"
type: docs
weight: 230
url: /fr/net/aspose.barcode.barcoderecognition/decodetype/
---
## DecodeType class

Spécifiez le type de code‑barres à lire.

```csharp
public static class DecodeType
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [AllSupportedTypesArray](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypesarray/) { get; } | Obtient un tableau qui représente AllSupportedTypes |

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetNames](../../aspose.barcode.barcoderecognition/decodetype/getnames/)() | Récupère un tableau des noms des types de décodage. |
| static [Is1D](../../aspose.barcode.barcoderecognition/decodetype/is1d/)(BaseDecodeType) | Détermine si le [`BaseDecodeType`](../basedecodetype/) spécifié contient une quelconque symbologie de code-barres 1D |
| static [Is2D](../../aspose.barcode.barcoderecognition/decodetype/is2d/)(BaseDecodeType) | Détermine si le [`BaseDecodeType`](../basedecodetype/) spécifié contient une quelconque symbologie de code-barres 2D |
| static [IsPostal](../../aspose.barcode.barcoderecognition/decodetype/ispostal/)(BaseDecodeType) | Détermine si le [`BaseDecodeType`](../basedecodetype/) spécifié contient une quelconque symbologie de code-barres postal |
| static [Parse](../../aspose.barcode.barcoderecognition/decodetype/parse/)(string, out SingleDecodeType) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [ScanSets](../../aspose.barcode.barcoderecognition/decodetype/scansets/)(params BaseDecodeType[]) | Spécifiez les ensembles de numérisation par barcodeTypes |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse)(string, out MultiDecodeType) | Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [TryParse](../../aspose.barcode.barcoderecognition/decodetype/tryparse/#tryparse_1)(string, out SingleDecodeType) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [AllSupportedTypes](../../aspose.barcode.barcoderecognition/decodetype/allsupportedtypes/) | Spécifie que les données seront vérifiées avec toutes les symbologies disponibles |
| static readonly [AustralianPosteParcel](../../aspose.barcode.barcoderecognition/decodetype/australianposteparcel/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Australian Post Domestic eParcel Barcode** |
| static readonly [AustraliaPost](../../aspose.barcode.barcoderecognition/decodetype/australiapost/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Australia Post** |
| static readonly [Aztec](../../aspose.barcode.barcoderecognition/decodetype/aztec/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Aztec** |
| static readonly [Codabar](../../aspose.barcode.barcoderecognition/decodetype/codabar/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODABAR** |
| static readonly [CodablockF](../../aspose.barcode.barcoderecognition/decodetype/codablockf/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CodablockF** |
| static readonly [Code11](../../aspose.barcode.barcoderecognition/decodetype/code11/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 11** |
| static readonly [Code128](../../aspose.barcode.barcoderecognition/decodetype/code128/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 128** |
| static readonly [Code16K](../../aspose.barcode.barcoderecognition/decodetype/code16k/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **SCode16K** |
| static readonly [Code32](../../aspose.barcode.barcoderecognition/decodetype/code32/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code32** |
| static readonly [Code39](../../aspose.barcode.barcoderecognition/decodetype/code39/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères de base : ISO/IEC 16388 |
| static readonly [Code39FullASCII](../../aspose.barcode.barcoderecognition/decodetype/code39fullascii/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Code 39** jeu de caractères ASCII complet : ISO/IEC 16388 |
| static readonly [Code93](../../aspose.barcode.barcoderecognition/decodetype/code93/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CODE 93** |
| static readonly [CompactPdf417](../../aspose.barcode.barcoderecognition/decodetype/compactpdf417/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **CompactPdf417** (Pdf417Truncated) |
| static readonly [DatabarExpanded](../../aspose.barcode.barcoderecognition/decodetype/databarexpanded/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar expanded** |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.barcoderecognition/decodetype/databarexpandedstacked/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar expanded stacked** |
| static readonly [DatabarLimited](../../aspose.barcode.barcoderecognition/decodetype/databarlimited/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar limited** |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databaromnidirectional/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar omni-directional** |
| static readonly [DatabarStacked](../../aspose.barcode.barcoderecognition/decodetype/databarstacked/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar stacked** |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.barcoderecognition/decodetype/databarstackedomnidirectional/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar stacked omni-directional** |
| static readonly [DatabarTruncated](../../aspose.barcode.barcoderecognition/decodetype/databartruncated/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Databar truncated** |
| static readonly [DataLogic2of5](../../aspose.barcode.barcoderecognition/decodetype/datalogic2of5/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DataLogic 2 of 5** |
| static readonly [DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/datamatrix/) | Spécifie que les données doivent être décodées avec la symbologie de code-barres **DataMatrix** |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostidentcode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Ident code** |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.barcoderecognition/decodetype/deutschepostleitcode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DeutschePost Leit code** |
| static readonly [DotCode](../../aspose.barcode.barcoderecognition/decodetype/dotcode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode** |
| static readonly [DutchKIX](../../aspose.barcode.barcoderecognition/decodetype/dutchkix/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **DotCode** |
| static readonly [EAN13](../../aspose.barcode.barcoderecognition/decodetype/ean13/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-13** |
| static readonly [EAN14](../../aspose.barcode.barcoderecognition/decodetype/ean14/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN14** |
| static readonly [EAN8](../../aspose.barcode.barcoderecognition/decodetype/ean8/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **EAN-8** |
| static readonly [GS1Aztec](../../aspose.barcode.barcoderecognition/decodetype/gs1aztec/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Aztec** |
| static readonly [GS1Code128](../../aspose.barcode.barcoderecognition/decodetype/gs1code128/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 CODE 128** |
| static readonly [GS1CompositeBar](../../aspose.barcode.barcoderecognition/decodetype/gs1compositebar/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Composite Bar** |
| static readonly [GS1DataMatrix](../../aspose.barcode.barcoderecognition/decodetype/gs1datamatrix/) | Spécifie que les données doivent être décodées avec la symbologie de code-barres **GS1DataMatrix** |
| static readonly [GS1DotCode](../../aspose.barcode.barcoderecognition/decodetype/gs1dotcode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 DotCode** |
| static readonly [GS1HanXin](../../aspose.barcode.barcoderecognition/decodetype/gs1hanxin/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 Han Xin Code** |
| static readonly [GS1MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/gs1micropdf417/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MicroPdf417** |
| static readonly [GS1QR](../../aspose.barcode.barcoderecognition/decodetype/gs1qr/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **GS1 QR** |
| static readonly [HanXin](../../aspose.barcode.barcoderecognition/decodetype/hanxin/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Han Xin Code** |
| static readonly [HIBCAztecLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcazteclic/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Aztec** |
| static readonly [HIBCAztecPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcaztecpas/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Aztec** |
| static readonly [HIBCCode128LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode128lic/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code128** |
| static readonly [HIBCCode128PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode128pas/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code128** |
| static readonly [HIBCCode39LIC](../../aspose.barcode.barcoderecognition/decodetype/hibccode39lic/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC Code39** |
| static readonly [HIBCCode39PAS](../../aspose.barcode.barcoderecognition/decodetype/hibccode39pas/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS Code39** |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixlic/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC DataMatrix** |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcdatamatrixpas/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS DataMatrix** |
| static readonly [HIBCQRLIC](../../aspose.barcode.barcoderecognition/decodetype/hibcqrlic/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC LIC QR** |
| static readonly [HIBCQRPAS](../../aspose.barcode.barcoderecognition/decodetype/hibcqrpas/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **HIBC PAS QR** |
| static readonly [IATA2of5](../../aspose.barcode.barcoderecognition/decodetype/iata2of5/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **IATA 2 of 5**. IATA (International Air Transport Association) utilise ce code-barres pour la gestion du fret aérien. |
| static readonly [Interleaved2of5](../../aspose.barcode.barcoderecognition/decodetype/interleaved2of5/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **INTERLEAVED 2 of 5** |
| static readonly [ISBN](../../aspose.barcode.barcoderecognition/decodetype/isbn/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISBN** |
| static readonly [ISMN](../../aspose.barcode.barcoderecognition/decodetype/ismn/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISMN** |
| static readonly [ISSN](../../aspose.barcode.barcoderecognition/decodetype/issn/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ISSN** |
| static readonly [ItalianPost25](../../aspose.barcode.barcoderecognition/decodetype/italianpost25/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Italian Post 25** |
| static readonly [ITF14](../../aspose.barcode.barcoderecognition/decodetype/itf14/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF14** |
| static readonly [ITF6](../../aspose.barcode.barcoderecognition/decodetype/itf6/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **ITF6** |
| static readonly [JapanPost](../../aspose.barcode.barcoderecognition/decodetype/japanpost/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Japan Post** |
| static readonly [MacroPdf417](../../aspose.barcode.barcoderecognition/decodetype/macropdf417/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MacroPdf417** |
| static readonly [Mailmark](../../aspose.barcode.barcoderecognition/decodetype/mailmark/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Royal Mail Mailmark** |
| static readonly [Matrix2of5](../../aspose.barcode.barcoderecognition/decodetype/matrix2of5/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Matrix 2 of 5** |
| static readonly [MaxiCode](../../aspose.barcode.barcoderecognition/decodetype/maxicode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MaxiCode** |
| static readonly [MicrE13B](../../aspose.barcode.barcoderecognition/decodetype/micre13b/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MICR E-13B** |
| static readonly [MicroPdf417](../../aspose.barcode.barcoderecognition/decodetype/micropdf417/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MicroPdf417** |
| static readonly [MicroQR](../../aspose.barcode.barcoderecognition/decodetype/microqr/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MicroQR Code** |
| static readonly [MostCommonTypes](../../aspose.barcode.barcoderecognition/decodetype/mostcommontypes/) | Spécifie que les données seront vérifiées avec les symbologies les plus couramment utilisées |
| static readonly [MSI](../../aspose.barcode.barcoderecognition/decodetype/msi/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **MSI Plessey** |
| static readonly [None](../../aspose.barcode.barcoderecognition/decodetype/none/) | Type de décodage non spécifié. |
| static readonly [OneCode](../../aspose.barcode.barcoderecognition/decodetype/onecode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres USPS **OneCode** |
| static readonly [OPC](../../aspose.barcode.barcoderecognition/decodetype/opc/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **OPC** |
| static readonly [PatchCode](../../aspose.barcode.barcoderecognition/decodetype/patchcode/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Patch code**. La symbologie de code-barres est utilisée pour le balayage automatisé |
| static readonly [Pdf417](../../aspose.barcode.barcoderecognition/decodetype/pdf417/) | Spécifie que les données doivent être décodées avec la symbologie de code-barres **Pdf417** |
| static readonly [Pharmacode](../../aspose.barcode.barcoderecognition/decodetype/pharmacode/) | Spécifie que les données doivent être décodées avec le code-barres **Pharmacode**. Cette symbologie est également connue sous le nom de Pharmaceutical Binary Code |
| static readonly [Planet](../../aspose.barcode.barcoderecognition/decodetype/planet/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Planet** |
| static readonly [PostalTypes](../../aspose.barcode.barcoderecognition/decodetype/postaltypes/) | Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **1.5D Postal**, comme **Planet, Postnet, AustraliaPost, JapanPost, OneCode, RM4SCC, DutchKIX**. |
| static readonly [Postnet](../../aspose.barcode.barcoderecognition/decodetype/postnet/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Postnet** |
| static readonly [PZN](../../aspose.barcode.barcoderecognition/decodetype/pzn/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **PZN**. Cette symbologie est également connue sous le nom de Pharma Zentral Nummer. PZN7 et PZN8 sont pris en charge. |
| static readonly [QR](../../aspose.barcode.barcoderecognition/decodetype/qr/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **QR Code** |
| static readonly [RectMicroQR](../../aspose.barcode.barcoderecognition/decodetype/rectmicroqr/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **RectMicroQR (rMQR) Code** |
| static readonly [RM4SCC](../../aspose.barcode.barcoderecognition/decodetype/rm4scc/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **RM4SCC**. RM4SCC (Royal Mail 4-state Customer Code) est utilisé pour le processus de tri automatisé du courrier au Royaume-Uni. |
| static readonly [SCC14](../../aspose.barcode.barcoderecognition/decodetype/scc14/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **SCC14** |
| static readonly [SSCC18](../../aspose.barcode.barcoderecognition/decodetype/sscc18/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **SSCC18** |
| static readonly [Standard2of5](../../aspose.barcode.barcoderecognition/decodetype/standard2of5/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Standard 2 of 5** |
| static readonly [Supplement](../../aspose.barcode.barcoderecognition/decodetype/supplement/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Supplement(EAN2, EAN5)** |
| static readonly [SwissPostParcel](../../aspose.barcode.barcoderecognition/decodetype/swisspostparcel/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **Swiss Post Parcel Barcode** |
| static readonly [Types1D](../../aspose.barcode.barcoderecognition/decodetype/types1d/) | Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **1D**. |
| static readonly [Types2D](../../aspose.barcode.barcoderecognition/decodetype/types2d/) | Spécifie que les données seront vérifiées avec toutes les symbologies de code-barres **2D**. |
| static readonly [UPCA](../../aspose.barcode.barcoderecognition/decodetype/upca/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **UPC-A** |
| static readonly [UPCE](../../aspose.barcode.barcoderecognition/decodetype/upce/) | Spécifie que les données doivent être décodées avec la spécification de code-barres **UPC-E** |
| static readonly [VIN](../../aspose.barcode.barcoderecognition/decodetype/vin/) | Spécifie que les données doivent être décodées selon la spécification de code-barres **VIN** (Vehicle Identification Number) |

## Exemples

Cet exemple montre comment détecter les codes-barres Code39 et Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



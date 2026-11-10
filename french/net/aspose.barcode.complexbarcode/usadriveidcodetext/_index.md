---
title: "Classe USADriveIdCodetext"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.USADriveIdCodetext. Classe pour l'encodage et le décodage du texte intégré dans le code PDF417 du permis de conduire américain."
type: docs
weight: 810
url: /fr/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code PDF417 du permis de conduire USA.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Numéro de version AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Ce numéro identifie de manière unique la juridiction émettrice et peut être obtenu en contactant l'Autorité d'émission ISO (AAMVA). Le IIN complet à 6 chiffres doit être encodé. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Champs spécifiques à la juridiction |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Numéro de version de la juridiction 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Éléments obligatoires (champs) de la carte |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Nombre 00-99 de sous‑fichiers |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Éléments (champs) optionnels de la carte |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Contient des informations sur les sous‑fichiers suivants, leurs types, décalages et longueurs. Important : définissez uniquement le type, le décalage et la longueur seront définis automatiquement. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Renvoie le type de code-barres du permis de conduire américain (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Construit le codetext à partir des données du permis de conduire américain |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Initialise l'objet du permis de conduire américain à partir du codetext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Enregistre au format XML |

## Autres membres

| Nom | Description |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Éléments obligatoires (champs) de la carte |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Éléments (champs) optionnels de la carte |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Les propriétés du sous-fichier USA DL, le décalage et la longueur sont définis automatiquement. |

### Voir aussi

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



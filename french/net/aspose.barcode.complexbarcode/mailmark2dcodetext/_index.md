---
title: "Classe Mailmark2DCodetext"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext. Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark."
type: docs
weight: 650
url: /fr/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Identifie la classe de l'élément. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Espace facultatif à l'usage du client. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Mode d'encodage du code-barres Datamatrix. Valeur par défaut : EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Contient le code postal de l'adresse de livraison avec le DPS. Si le lieu est intérieur, le code postal/DP comporte le nombre de caractères suivant : zone (1 ou 2 caractères), district (1 ou 2 caractères), secteur (1 caractère), unité (2 caractères), DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Identifie la charge utile du code-barres Mailmark de Royal Mail pour chaque type de produit. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit porter un ID afin d'être identifié de manière unique pendant au moins 90 jours. Valeur maximale : 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Contient le code postal de retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Indicateur qui indique le niveau de service de retour à l'expéditeur demandé. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Identifie l'ID pays UPU. Longueur maximale : 4 caractères. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Identifie la version du code-barres pertinente pour chaque ID de type d'information. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Obtient le type de code-barres. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Construire le texte de code à partir des données Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Initialise les données Mailmark à partir du texte de code construit. |

### Voir aussi

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



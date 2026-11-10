---
title: "Class GS1DigitalLink"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.GS1DigitalLink. Représente le texte de code GS1 Digital Link pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'Identifiant d'Application. L'ordre d'origine et les Identifiants d'Application répétés sont conservés. Le texte de code construit est une URI GS1 Digital Link non compressée. Les paramètres de requête non GS1 et les fragments d'URI sont ignorés lors de l'analyse."
type: docs
weight: 540
url: /fr/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Représente le texte de code GS1 Digital Link pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'Identifiant d'Application. L'ordre d'origine et les Identifiants d'Application répétés sont conservés. Le texte de code construit est une URI GS1 Digital Link non compressée. Les paramètres de requête et les fragments d'URI non GS1 sont ignorés lors de l'analyse.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Initialise un GS1 Digital Link vide avec le tronc d'URI spécifié. La clé primaire est sélectionnée automatiquement lorsqu'un seul candidat à la clé primaire est présent. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Initialise un GS1 Digital Link vide avec le tronc d'URI spécifié et la clé primaire. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Obtient ou définit le type de code-barres utilisé pour encoder ce lien numérique GS1. Les types pris en charge sont QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF et Code128. La valeur par défaut est QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Obtient le nombre d'éléments d'identifiant d'application. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Obtient une copie de tous les éléments dans l'ordre d'origine. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Obtient un élément par sa position dans la séquence ordonnée. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Obtient l'identifiant d'application utilisé comme clé primaire du lien numérique. Null signifie que la clé primaire est sélectionnée automatiquement lors de la construction de l'URI. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Obtient le préfixe d'URI absolu avant le segment de chemin de la clé primaire GS1. Le tronc ne contient pas de chaîne de requête ni de fragment. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Crée un lien numérique GS1 en copiant tous les éléments du codetext GS1 et en sélectionnant la seule clé primaire disponible. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Crée un lien numérique GS1 en copiant tous les éléments du codetext GS1 et en utilisant la clé primaire spécifiée. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Analyse une URI de lien numérique GS1 non compressée. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Ajoute un élément d'identifiant d'application validé. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Obtient toutes les valeurs d'un identifiant d'application dans l'ordre d'origine. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Obtient le type de code-barres utilisé pour encoder ce lien numérique GS1. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Construit l'URI du lien numérique GS1 non compressée. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Obtient la première valeur d'un identifiant d'application. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Initialise cette instance à partir d'une URI de lien numérique GS1 non compressée. L'état existant n'est remplacé qu'après que l'URI fournie a été analysée avec succès. Le type de code-barres sélectionné est conservé. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Crée un codetext GS1 indépendant contenant les éléments GS1 actuels. Les informations uniquement d'URI ne sont pas incluses. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Renvoie l'URI du lien numérique GS1 non compressée. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formate l'état actuel de l'objet en tant qu'URI de lien numérique GS1 non compressée. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Tente d'analyser une URI de lien numérique GS1 non compressée et renvoie des erreurs de validation structurées. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Valide une URI de lien numérique GS1 non compressée sans construire d'objet. |

### Voir aussi

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



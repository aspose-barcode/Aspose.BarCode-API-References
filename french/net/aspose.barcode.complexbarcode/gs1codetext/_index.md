---
title: "Classe GS1Codetext"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.GS1Codetext. Représente le codetext GS1 pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'identifiant d'application. L'ordre d'origine et les identifiants d'application répétés sont conservés. La représentation entre crochets a la forme AIvalueAIvalue. Une parenthèse ouvrante littérale  à l'intérieur d'une valeur doit être écrite comme  c'est la seule séquence d'échappement prise en charge. Une parenthèse fermante  à l'intérieur d'une valeur ne nécessite pas d'échappement"
type: docs
weight: 530
url: /fr/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Représente le texte de code GS1 pour l'encodage et le décodage sous forme d'une séquence ordonnée d'éléments d'Identifiant d'Application. L'ordre d'origine et les Identifiants d'Application répétés sont conservés. La représentation entre parenthèses a la forme (AI)valeur(AI)valeur. Une parenthèse ouvrante littérale '(' à l'intérieur d'une valeur doit être écrite comme \\(; c'est la seule séquence d'échappement prise en charge. Une parenthèse fermante ')' à l'intérieur d'une valeur ne nécessite pas d'échappement.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Obtient ou définit le type de code-barres utilisé pour encoder ce codetext GS1. Les types pris en charge sont GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR et les types GS1 DataBar. La valeur par défaut est GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Obtient le nombre d'éléments d'identifiant d'application. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Obtient une copie de tous les éléments dans l'ordre d'origine. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Obtient un élément par sa position dans la séquence ordonnée. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Analyse une chaîne d'élément GS1 entre crochets sous la forme (AI)value(AI)value. Un '(' littéral à l'intérieur d'une valeur doit être écrit comme \(; aucune autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas d'échappement. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Ajoute un élément d'identifiant d'application validé. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Obtient toutes les valeurs d'un identifiant d'application dans l'ordre d'origine. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Obtient le type de code-barres utilisé pour encoder ce codetext GS1. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Construit le texte codé GS1 entre crochets sous la forme (AI)valeur(AI)valeur. Les parenthèses ouvrantes littérales dans les valeurs sont échappées comme \(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Obtient la première valeur d'un identifiant d'application. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Initialise cette instance à partir du texte codé GS1 entre crochets sous la forme (AI)valeur(AI)valeur. Les éléments existants ne sont remplacés qu'après que le texte codé fourni a été analysé avec succès. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Renvoie la représentation GS1 entre crochets sous la forme (AI)valeur(AI)valeur. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Tente d'analyser une chaîne d'élément GS1 entre crochets sous la forme (AI)valeur(AI)valeur et renvoie des erreurs de validation structurées. Un '(' littéral à l'intérieur d'une valeur doit être écrit comme \(; aucune autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas d'échappement. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Valide une chaîne d'élément GS1 entre crochets sous la forme (AI)valeur(AI)valeur sans créer d'objet. Un '(' littéral à l'intérieur d'une valeur doit être écrit comme \(; aucune autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas d'échappement. |

### Voir aussi

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



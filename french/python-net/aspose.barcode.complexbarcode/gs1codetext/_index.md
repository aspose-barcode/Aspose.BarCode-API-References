---
title: "GS1Codetext"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Représente le texte codé GS1 pour l'encodage et le décodage sous forme d'une séquence ordonnée de<br/>            éléments d'Identifiant d'Application. L'ordre source et les Identifiants d'Application répétés<br/>            sont conservés. La représentation entre parenthèses a la forme (AI)value(AI)value.<br/>            Une parenthèse ouvrante littérale '(' à l'intérieur d'une valeur doit être écrite comme \(; c'est la<br/>            seule séquence d'échappement prise en charge. Une parenthèse fermante ')' à l'intérieur d'une valeur n'est pas<br/>            nécessaire d'être échappée.

Le type GS1Codetext expose les membres suivants :
## Constructeurs
| Name | Description |
| :- | :- |
| GS1Codetext() | Initialise une nouvelle instance de la classe GS1Codetext |
## Properties
| Name | Description |
| :- | :- |
| barcode_type | Obtient ou définit le type de code-barres utilisé pour encoder ce texte GS1.<br/>            Les types pris en charge sont GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR et les types GS1 DataBar.<br/>            La valeur par défaut est GS1Code128. |
| count | Obtient le nombre d'éléments d'identifiant d'application. |
| éléments | Obtient une copie de tous les éléments dans l'ordre d'origine. |
## Indexer
| Name | Description |
| :- | :- |
| [index] | Obtient un élément par sa position dans la séquence ordonnée. |
## Methods
| Name | Description |
| :- | :- |
| get_first(application_identifier) | Obtient la première valeur pour un identifiant d'application. |
| get_all(application_identifier) | Obtient toutes les valeurs pour un identifiant d'application dans l'ordre d'origine. |
| add(application_identifier, value) | Ajoute un élément d'identifiant d'application validé. |
| validate(value) | Valide une chaîne d'élément GS1 entre parenthèses sous la forme (AI)value(AI)value sans<br/>            construire un objet. Un '(' littéral à l'intérieur d'une valeur doit être écrit comme \(; aucune<br/>            autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas d'échappement. |
| parse(value) | Analyse une chaîne d'élément GS1 entre parenthèses sous la forme (AI)value(AI)value. Un '(' littéral<br/>            à l'intérieur d'une valeur doit être écrit comme \(; aucune autre séquence d'échappement n'est prise en charge,<br/>            et ')' ne nécessite pas d'échappement. |
| try_parse(value, result, validation_result) | Tente d'analyser une chaîne d'élément GS1 entre parenthèses sous la forme (AI)value(AI)value<br/>            et renvoie des erreurs de validation structurées. Un '(' littéral à l'intérieur d'une valeur doit être<br/>            écrit comme \(; aucune autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas<br/>            d'échappement. |
| get_constructed_codetext() | Construit le texte codé GS1 entre parenthèses sous la forme (AI)value(AI)value.<br/>            Les parenthèses ouvrantes littérales dans les valeurs sont échappées comme \(. |
| init_from_string(constructed_codetext) | Initialise cette instance à partir d'un texte codé GS1 entre parenthèses sous la forme (AI)value(AI)value.<br/>            Les éléments existants ne sont remplacés qu'après que le texte fourni a été analysé avec succès. |
| get_barcode_type() | Obtient le type de code-barres utilisé pour encoder ce texte GS1. |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


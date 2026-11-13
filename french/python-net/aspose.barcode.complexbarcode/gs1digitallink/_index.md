---
title: "GS1DigitalLink"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Représente le texte codé GS1 Digital Link pour l'encodage et le décodage sous forme d'une séquence ordonnée de<br/>            éléments d'Identifiant d'Application. L'ordre source et les Identifiants d'Application répétés sont conservés.<br/>            Le texte codé construit est une URI GS1 Digital Link non compressée.<br/>            Les paramètres de requête non GS1 et les fragments d'URI sont ignorés lors de l'analyse.

Le type GS1DigitalLink expose les membres suivants :
## Constructeurs
| Name | Description |
| :- | :- |
| GS1DigitalLink(uri_stem) | Initialise une nouvelle instance de la classe GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Initialise une nouvelle instance de la classe GS1DigitalLink |
## Properties
| Name | Description |
| :- | :- |
| uri_stem | Obtient le préfixe URI absolu avant le segment de chemin de la clé primaire GS1.<br/>            Le tronc ne contient pas de chaîne de requête ni de fragment. |
| primary_application_identifier | Obtient l'identifiant d'application utilisé comme clé primaire du Digital Link.<br/>            Null signifie que la clé primaire est sélectionnée automatiquement lors de la construction de l'URI. |
| barcode_type | Obtient ou définit le type de code-barres utilisé pour encoder ce GS1 Digital Link.<br/>            Les types pris en charge sont QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF et Code128.<br/>            La valeur par défaut est QR. |
| count | Obtient le nombre d'éléments d'identifiant d'application. |
| éléments | Obtient une copie de tous les éléments dans l'ordre d'origine. |
## Indexer
| Name | Description |
| :- | :- |
| [index] | Obtient un élément par sa position dans la séquence ordonnée. |
## Methods
| Name | Description |
| :- | :- |
| create(uri_stem, codetext) | Crée un GS1 Digital Link en copiant tous les éléments du codetext GS1 et en sélectionnant<br/>            la seule clé primaire disponible. |
| create(uri_stem, codetext, primary_application_identifier) | Crée un GS1 Digital Link en copiant tous les éléments du codetext GS1 et en sélectionnant<br/>            la seule clé primaire disponible. |
| get_first(application_identifier) | Obtient la première valeur pour un identifiant d'application. |
| get_all(application_identifier) | Obtient toutes les valeurs pour un identifiant d'application dans l'ordre d'origine. |
| add(application_identifier, value) | Ajoute un élément d'identifiant d'application validé. |
| validate(value) | Valide une URI GS1 Digital Link non compressée sans créer d'objet. |
| parse(value) | Analyse une URI GS1 Digital Link non compressée. |
| try_parse(value, result, validation_result) | Tente d'analyser une URI GS1 Digital Link non compressée et renvoie des erreurs de validation structurées. |
| to_gs1_codetext() | Crée un codetext GS1 indépendant contenant les éléments GS1 actuels.<br/>            Les informations uniquement d'URI ne sont pas incluses. |
| to_uri_string() | Formate l'état actuel de l'objet en tant qu'URI GS1 Digital Link non compressé. |
| get_constructed_codetext() | Construit l'URI GS1 Digital Link non compressé. |
| init_from_string(constructed_codetext) | Initialise cette instance à partir d'une URI GS1 Digital Link non compressée.<br/>            L'état existant n'est remplacé qu'après que l'URI fourni a été analysé avec succès.<br/>            Le type de code-barres sélectionné est préservé. |
| get_barcode_type() | Obtient le type de code-barres utilisé pour encoder ce GS1 Digital Link. |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


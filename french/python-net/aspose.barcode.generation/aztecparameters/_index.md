---
title: "AztecParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Paramètres Aztec.

Le type AztecParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| encode_mode | Obtient ou définit un mode d'encodage Aztec. <br/>            Valeur par défaut : Auto. |
| eci_encoding | Obtient ou définit l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto.<br/>            Valeur par défaut : ISO-8859-1 |
| structured_append_barcode_id | ID du code-barres pour le mode Structured Append du code-barres Aztec. L'ID du code-barres doit être compris entre 1 et le nombre total de codes-barres.<br/>            Valeur par défaut : 0 |
| structured_append_barcodes_count | Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26.<br/>            Valeur par défaut : 0 |
| structured_append_file_id | Identifiant de fichier pour le mode Structured Append du code Aztec (champ facultatif). L'identifiant de fichier ne doit pas contenir d'espaces.<br/>            Valeur par défaut : chaîne vide |
| error_level | Niveau de correction d'erreur des types de code Aztec.<br/>            La valeur doit être comprise entre 5 et 95. |
| symbol_mode | Obtient ou définit un mode de symbole Aztec.<br/>            Valeur par défaut : AztecSymbolMode.Auto. |
| layers_count | Obtient ou définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et<br/>            entre 1 et 32 pour le mode Full Range.<br/>            Valeur par défaut : 0 (auto). |
| is_reader_initialization | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole<br/>            comme une programmation pour l'initialisation du lecteur. |
| aspect_ratio | Ratio hauteur/largeur du module de code-barres 2D. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


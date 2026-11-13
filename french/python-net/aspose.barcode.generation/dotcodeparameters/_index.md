---
title: "DotCodeParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/dotcodeparameters/
---

## DotCodeParameters class

Paramètres DotCode.

Le type DotCodeParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| aspect_ratio | Ratio hauteur/largeur du module de code-barres 2D. |
| encode_mode | Identifie le mode d’encodage DotCode. <br/>            Valeur par défaut : Auto. |
| is_reader_initialization | Indique si le code est utilisé pour instruire le lecteur à interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de code-barres.<br/>            Valeur par défaut : false. |
| structured_append_mode_barcode_id | Identifie l’ID du code-barres en mode d’ajout structuré DotCode. L’ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. |
| structured_append_mode_barcodes_count | Identifie le nombre de codes-barres en mode d’ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. |
| eci_encoding | Identifie l’encodage ECI. Utilisé lorsque DotCodeEncodeMode est Auto.<br/>            Valeur par défaut : ISO-8859-1 |
| lignes | Identifie le nombre de lignes. La somme du nombre de lignes et du nombre de colonnes d’un symbole DotCode doit être impaire. Le nombre de lignes doit être au moins 5.<br/>            Valeur par défaut : -1 |
| colonnes | Identifie le nombre de colonnes. La somme du nombre de lignes et du nombre de colonnes d’un symbole DotCode doit être impaire. Le nombre de colonnes doit être au moins 5.<br/>            Valeur par défaut : -1 |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


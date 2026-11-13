---
title: "DataMatrixParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Paramètres DataMatrix.

Le type DataMatrixParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| ecc_type | Obtient ou définit un type ECC Datamatrix.<br/>            Valeur par défaut : DataMatrixEccType.Ecc200. |
| version | Obtient ou définit la taille du symbole Datamatrix.<br/>            Valeur par défaut : Version.Auto. |
| encode_mode | Mode d'encodage du code-barres Datamatrix.<br/>            Valeur par défaut : EncodeMode.Auto. |
| structured_append_barcode_id | ID du code-barres pour le mode Structured Append du code-barres Datamatrix.<br/>            Valeur par défaut : 0 |
| structured_append_barcodes_count | Nombre de codes-barres pour le mode Structured Append du code-barres Datamatrix.<br/>            Valeur par défaut : 0 |
| structured_append_file_id | ID du fichier pour le mode Structured Append du code-barres Datamatrix.<br/>            Valeur par défaut : 0 |
| is_reader_programming | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole<br/>            comme une programmation pour l'initialisation du lecteur.<br/>            Valeur par défaut : false |
| macro_characters | Les valeurs Macro Characters 05 et 06 sont utilisées pour obtenir un encodage plus compact dans les modes spéciaux.<br/>            Ne peuvent être utilisées qu'avec DataMatrixEccType.Ecc200 ou DataMatrixEccType.EccAuto.<br/>            Ne peuvent pas être utilisées avec EncodeTypes.GS1DataMatrix<br/>            Valeur par défaut : MacroCharacters.None. |
| aspect_ratio | Ratio hauteur/largeur du module de code-barres 2D. |
| eci_encoding | Obtient ou définit l'encodage ECI. Utilisé lorsque EncodeMode est Auto.<br/>            Valeur par défaut: ISO-8859-1 |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


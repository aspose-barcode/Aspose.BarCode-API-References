---
title: "BarcodeGenerator"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator pour la génération d'images de codes-barres côté serveur.

Le type BarcodeGenerator expose les membres suivants:
## Constructeurs
| Name | Description |
| :- | :- |
| BarcodeGenerator(type) | Initialise une nouvelle instance de la classe BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Initialise une nouvelle instance de la classe BarcodeGenerator |
## Properties
| Name | Description |
| :- | :- |
| paramètres | Paramètres de génération. |
| barcode_type | Type de symbologie du code-barres. |
| code_text | Texte à encoder. |
## Methods
| Name | Description |
| :- | :- |
| set_code_text(code_bytes) | Définit le texte du code comme une séquence d'octets. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Enregistre l'image du code-barres dans le flux dans un format spécifique. |
| save(filename, format) | Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique. |
| save(filename) | Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique. |
| export_to_xml(xml_file) | Exporte les propriétés BarCode vers le fichier xml spécifié |
| export_to_xml(xml) | Exporte les propriétés BarCode vers le flux xml spécifié |
| import_from_xml(xml_file) | Importe les propriétés BarCode du fichier xml spécifié et crée une instance de BarcodeGenerator. |
| import_from_xml(xml) | Importe les propriétés BarCode du flux xml spécifié et crée une instance de BarcodeGenerator. |
| generate_bar_code_image() | Génère l'image du code-barres avec les paramètres actuels. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


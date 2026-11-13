---
title: "USADriveIdCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code PDF417 du permis de conduire américain.

Le type USADriveIdCodetext expose les membres suivants:
## Constructeurs
| Name | Description |
| :- | :- |
| USADriveIdCodetext() | Initialise une nouvelle instance de la classe USADriveIdCodetext |
## Properties
| Name | Description |
| :- | :- |
| issuer_identification_number | Ce numéro identifie de manière unique <br/>            la juridiction émettrice et peut être obtenu en contactant l'ISO<br/>            Autorité d'émission (AAMVA).  Le IIN complet à 6 chiffres doit être encodé. |
| aamva_version_number | Numéro de version AAMVA 00-99 |
| jurisdiction_version_number | Numéro de version de la juridiction 00-99 |
| number_of_entries | Nombre 00-99 de sous‑fichiers |
| subfile_designator | Contient des informations sur les sous‑fichiers suivants, les types, les décalages et les longueurs. <br/>            Important : seuls le type, le décalage et la longueur seront définis automatiquement. |
| mandatory_elements | Éléments obligatoires (champs) de la carte |
| optional_elements | Éléments optionnels (champs) de la carte |
| jurisdiction_specific_subfile | Champs spécifiques à la juridiction |
## Methods
| Name | Description |
| :- | :- |
| get_constructed_codetext() | Construire le codetext à partir des données USA DL |
| init_from_string(constructed_codetext) | Initialiser l'objet USA DL à partir du codetext |
| get_barcode_type() | Renvoie le type de code‑barres du USA DL (Pdf417) |
| save_to_xml(stream) | Enregistre en XML |

### Voir aussi

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


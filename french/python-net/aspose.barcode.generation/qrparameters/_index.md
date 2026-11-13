---
title: "QrParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/qrparameters/
---

## QrParameters class

Paramètres QR.

Le type QrParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| eci_encoding | Identifiants d'interprétation de canal étendu. Il est utilisé pour fournir au lecteur de code-barres des détails<br/>            sur les références utilisées pour encoder les données dans le symbole.<br/>            L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.<br/>            Non pris en charge par MicroQR. |
| encode_mode | Type de symbologie QR du mode d'encodage du code-barres.<br/>            Valeur par défaut : QREncodeMode.Auto. |
| error_level | Niveau de correction d'erreurs Reed‑Solomon pour les codes-barres QR, MicroQR et RectMicroQR.<br/>             Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel. |
| version | Version du code QR. De Version1 à Version40.<br/>            La valeur par défaut est QRVersion.Auto. |
| micro_qr_version | Version du code MicroQR. De la version M1 à la version M4.<br/>            La valeur par défaut est MicroQRVersion.Auto. |
| rect_micro_qr_version | Version du code RectMicroQR. De la version R7x59 à la version R17x139.<br/>            La valeur par défaut est RectMicroQRVersion.Auto. |
| aspect_ratio | Ratio hauteur/largeur du module de code-barres 2D. |
| structured_append | Paramètres d'ajout structuré QR.<br/>            Le mode d'ajout structuré n'est pas pris en charge par les codes-barres MicroQR et RectMicroQR. |
| encode_gs1_separator_in_byte_mode |  |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


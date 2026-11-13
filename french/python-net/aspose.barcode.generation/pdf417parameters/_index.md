---
title: "Pdf417Parameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417.<br/>            MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels.<br/>            MicroPDF417 en mode Structured Append (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels.

Le type Pdf417Parameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| encode_mode | Identifie le mode d'encodage Pdf417.<br/>            Valeur par défaut : Auto. |
| error_level | Obtient ou définit le type de symbologie Pdf417 du niveau de correction d'erreur du BarCode<br/>            variant de level0 à level8, level0 signifie aucune information de correction d'erreur,<br/>            level8 signifie la meilleure correction d'erreur, ce qui implique une image plus grande. |
| truncate | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace).<br/>            Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode. |
| colonnes | Nombre de colonnes. |
| lignes | Nombre de lignes. |
| aspect_ratio | Ratio hauteur/largeur du module de code-barres 2D. |
| macro_pdf_417_file_id | Identifiant de fichier du code-barres MacroPdf417 (champ requis).<br/>            Identifiant de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append). |
| macro_pdf_417_segment_id | Identifiant de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1.<br/>            Identifiant de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append). |
| macro_pdf_417_segments_count | Nombre de segments du code-barres MacroPdf417 (champ optionnel).<br/>            Nombre de segments du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| macro_pdf_417_file_name | Nom de fichier du code-barres MacroPdf417 (champ optionnel).<br/>            Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| macro_pdf_417_time_stamp | Horodatage du code-barres MacroPdf417 (champ optionnel).<br/>            Horodatage du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| macro_pdf_417_sender | Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel).<br/>            Nom de l'expéditeur du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| macro_pdf_417_addressee | Nom du destinataire du code-barres MacroPdf417 (champ optionnel).<br/>            Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| macro_pdf_417_file_size | Taille du fichier MacroPdf417 (champ facultatif).<br/>            Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append)<br/>            Le champ taille du fichier contient la taille en octets du fichier source complet. |
| macro_pdf_417_checksum | Somme de contrôle du code-barres MacroPdf417 (champ facultatif).<br/>            Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append)<br/>            Le champ somme de contrôle contient la valeur de la somme de contrôle CRC de 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Identifiants d'interprétation de canal étendu. Il est utilisé pour indiquer au lecteur de code-barres les détails<br/>            sur les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417.<br/>            L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. |
| macro_pdf_417eci_encoding | Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417. |
| macro_pdf_417_terminator | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. <br/>            Appliqué uniquement pour Macro PDF417. |
| is_reader_initialization | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole<br/>            comme une programmation pour l'initialisation du lecteur. |
| macro_characters | Les valeurs Macro Characters 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux.<br/>            Ne peut être utilisé qu'avec MicroPdf417 et encode les modes MicroPdf417 916 et 917<br/>            Valeur par défaut : MacroCharacters.None. |
| is_linked | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417.<br/>            Avec la symbologie GS1MicroPdf417 encode les modes UCC/EAN-128 « Linked » 906, 907, 912, 913, 914, 915<br/>            Avec les symbologies MicroPdf417 et Pdf417 encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| is_code_128_emulation | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128.<br/>            Peut encoder FNC1 en position seconde dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


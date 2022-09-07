---
title: Pdf417Parameters
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Paramètres PDF417. Contient les paramètres PDF417 MacroPDF417 et MicroPDF417. MacroPDF417 nécessite deux champs  Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs. MicroPDF417 en mode dajout structuré identique au mode MacroPDF417 nécessite deux champs  Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs.
type: docs
weight: 860
url: /fr/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417 et MicroPDF417. MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs. MicroPDF417 en mode d'ajout structuré (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont facultatifs.

```csharp
public class Pdf417Parameters
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | Rapport hauteur/largeur du module 2D BarCode. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Mot de code de fonction pour l'émulation Code 128. Appliqué pour MicroPDF417 uniquement. Ignoré pour les codes-barres PDF417 et MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Obtient ou définit l'encodage du texte de code. Valeur par défaut : UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Nombre de colonnes. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Utilisé pour demander au lecteur d'interpréter les données contenues dans le symbole comme programmation pour l'initialisation du lecteur. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Type de symbologie Pdf417 du mode de compactage de BarCode. Valeur par défaut : Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Identificateurs d'interprétation de canal étendu. Il est utilisé pour indiquer au lecteur de code-barres details les références utilisées pour encoder les données dans le symbole. Non appliqué pour les champs de texte Macro PDF417. L'implémentation actuelle comprend tous les codages de jeu de caractères bien connus. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | Obtient ou définit le type de symbologie Pdf417 du niveau de correction d'erreur de BarCode allant du niveau 0 au niveau 8, le niveau 0 signifie aucune information de correction d'erreur, le niveau 8 signifie la meilleure correction d'erreur, ce qui signifie une image plus grande. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Append structuré) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode d'ajout structuré) Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC 16 bits (2 octets) utilisant le polynôme CCITT-16. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Identificateurs d'interprétation de canal étendu. S'applique aux champs de texte Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | ID de fichier du code-barres MacroPdf417 (champ obligatoire). ID de fichier du code-barres MicroPDF417 (champ obligatoire pour le mode d'ajout structuré) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | Nom du fichier de code-barres MacroPdf417 (champ facultatif). Nom du fichier de code-barres MicroPDF417 (champ facultatif pour le mode d'ajout structuré) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode d'ajout structuré) Le champ Taille du fichier contient la taille en octets de l'intégralité du fichier source. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | ID de segment du code-barres MacroPdf417 (champ obligatoire), qui commence à partir de 0, jusqu'à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ obligatoire pour le mode d'ajout structuré) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | Nombre de segments de code-barres MacroPdf417 (champ facultatif). Nombre de segments de code-barres MicroPDF417 (champ facultatif pour le mode Append structuré) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode d'ajout structuré) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode d'ajout structuré) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | Si le type de symbologie Pdf417 de BarCode est tronqué (pour réduire l'espace). Également appelé CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Nombre de lignes. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce[`Pdf417Parameters`](../pdf417parameters) . |

### Voir également

* espace de noms [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

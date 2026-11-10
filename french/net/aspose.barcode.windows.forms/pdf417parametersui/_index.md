---
title: "Classe Pdf417ParametersUI"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Windows.Forms.Pdf417ParametersUI. Enveloppe UI pour la classe Pdf417Parameters"
type: docs
weight: 1860
url: /fr/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

Enveloppe UI pour la classe [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/).

```csharp
public class Pdf417ParametersUI
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Nombre de colonnes. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | Type de symbologie Pdf417 du mode d'encodage du BarCode. Valeur par défaut : Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | Obtient ou définit le type de symbologie Pdf417 du niveau de correction d'erreurs du BarCode, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui implique une image plus grande. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes « Linked » UCC/EAN-128 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Les valeurs des caractères Macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec MicroPdf417 et encodent les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC de 16 bits (2 octets) utilisant le polynôme CCITT‑16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Obtient ou définit l'identifiant de fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append) Le champ de taille du fichier contient la taille en octets du fichier source complet. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Obtient ou définit l'ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Obtient ou définit le nombre de segments du code-barres macro Pdf417. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. Appliqué uniquement pour Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Nombre de lignes. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Renvoie une représentation sous forme de chaîne lisible de cet [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/). |

### Voir aussi

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)



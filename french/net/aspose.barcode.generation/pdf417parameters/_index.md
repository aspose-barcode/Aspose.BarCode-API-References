---
title: "Classe Pdf417Parameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.Pdf417Parameters classe. Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417. MacroPDF417 nécessite deux champs Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels. MicroPDF417 en mode Structured Append, identique au mode MacroPDF417, nécessite deux champs Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels."
type: docs
weight: 1570
url: /fr/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417. MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels. MicroPDF417 en mode Structured Append (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels.

```csharp
public class Pdf417Parameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Ratio hauteur/largeur du module de code-barres 2D. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Nombre de colonnes. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | Obtient ou définit le type de symbologie Pdf417 du niveau de correction d'erreurs du BarCode, allant de level0 à level8, level0 signifie aucune information de correction d'erreurs, level8 signifie la meilleure correction d'erreurs, ce qui implique une image plus grande. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes « Linked » UCC/EAN-128 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Les valeurs des caractères Macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu'avec MicroPdf417 et encodent les modes MicroPdf417 916 et 917. Valeur par défaut : MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | Nom du destinataire du code-barres MacroPdf417 (champ facultatif). Nom du destinataire du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | Somme de contrôle du code-barres MacroPdf417 (champ facultatif). Somme de contrôle du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append). Le champ de somme de contrôle contient la valeur de la somme de contrôle CRC de 16 bits (2 octets) utilisant le polynôme CCITT‑16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Identifiants d'Interprétation de Canal Étendu. S'applique aux champs texte Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | Identifiant de fichier du code-barres MacroPdf417 (champ requis). Identifiant de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | Nom de fichier du code-barres MacroPdf417 (champ facultatif). Nom de fichier du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | Taille du fichier MacroPdf417 (champ facultatif). Taille du fichier MicroPDF417 (champ facultatif pour le mode Structured Append) Le champ de taille du fichier contient la taille en octets du fichier source complet. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | Identifiant de segment du code-barres MacroPdf417 (champ requis), qui commence à 0 et va jusqu'à MacroSegmentsCount - 1. Identifiant de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | Nombre de segments du code-barres MacroPdf417 (champ optionnel). Nombre de segments du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | Nom de l'expéditeur du code-barres MacroPdf417 (champ facultatif). Nom de l'expéditeur du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (code mot 922) au segment. Appliqué uniquement pour Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Nombre de lignes. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | Indique si le type de symbologie Pdf417 du BarCode est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `Pdf417Parameters`. |

## Exemples

Ces exemples montrent comment encoder les modes non liés UCC/EAN-128 dans GS1MicroPdf417.

```csharp
[C#]
//Encode le mode non lié 905 de GS1 UCC/EAN-128 avec l'AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Encode les modes non liés 903, 904 de GS1 UCC/EAN-128 avec n'importe quel AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



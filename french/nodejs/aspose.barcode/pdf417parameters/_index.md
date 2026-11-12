---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres PDF417."
type: docs
weight: 770
url: /fr/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Paramètres PDF417. Contient les paramètres PDF417, MacroPDF417, MicroPDF417 et GS1MicroPdf417. MacroPDF417 nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels. MicroPDF417 en mode Structured Append (identique au mode MacroPDF417) nécessite deux champs : Pdf417MacroFileID et Pdf417MacroSegmentID. Tous les autres champs sont optionnels. Ces exemples montrent comment encoder les modes non liés UCC/EAN-128 dans GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [getColumns()](#getcolumns) | Nombre de colonnes. |
| [getECIEncoding()](#geteciencoding) | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [getEncodeMode()](#getencodemode) | Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto. |
| [getErrorLevel()](#geterrorlevel) | Obtient le type de symbologie Pdf417 du niveau de correction d'erreur du BarCode, allant de level0 à level8, level0 signifie aucune correction d'erreur |
| [getMacroCharacters()](#getmacrocharacters) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Ne peut être utilisé qu'avec Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Identifiant de fichier du code-barres MacroPdf417 (champ requis). Identifiant de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append) La taille du fichier |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Identifiant de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Nombre de segments du code-barres MacroPdf417 (champ optionnel). Nombre de segments du code-barres MicroPDF417 (champ optionnel pour Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l'expéditeur du code-barres MicroPDF417 (champ optionnel pour Structured Append |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PD. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Horodatage du code-barres MacroPdf417 (champ optionnel). Horodatage du code-barres MicroPDF417 (champ optionnel pour Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Obtient le type de symbologie Pdf417 du niveau de correction d'erreur du BarCode, allant de level0 à level8, level0 signifie aucune correction d'erreur |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Obtient le nom du destinataire du code-barres macro Pdf417. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Obtient la somme de contrôle du code-barres macro Pdf417. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Obtient l'identifiant de fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Obtient le nom de fichier du code-barres macro Pdf417. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Obtient la taille du fichier macro Pdf417. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Obtient l'identifiant de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Obtient le nombre de segments du code-barres macro Pdf417. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Obtient le nom de l'expéditeur du code-barres macro Pdf417. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PD. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Obtient l'horodatage du code-barres macro Pdf417. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). |
| [getRows()](#getrows) | Nombre de lignes. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Identifie l'ID du code-barres en mode Structured Append de DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres |
| [getTruncate()](#gettruncate) | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. Indicatif de ligne droite |
| [isCode128Emulation()](#iscode128emulation) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et |
| [isLinked()](#islinked) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. La symbologie GS1MicroPdf417 encode 906, 907 |
| [isReaderInitialization()](#isreaderinitialization) | Utilisé pour indiquer au lecteur d’interpréter les données contenues dans le symbole comme une programmation pour l’initialisation du lecteur |
| [setAspectRatio()](#setaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [setCode128Emulation()](#setcode128emulation) | Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et |
| [setColumns()](#setcolumns) | Nombre de colonnes. |
| [setECIEncoding()](#seteciencoding) | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [setEncodeMode()](#setencodemode) | Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Définit le type de symbologie Pdf417 du niveau de correction d’erreur du BarCode allant de level0 à level8, level0 signifie aucune correction d’erreur |
| [setLinked()](#setlinked) | Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. La symbologie GS1MicroPdf417 encode 906, 907 |
| [setMacroCharacters()](#setmacrocharacters) | Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Ne peut être utilisé qu'avec Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | Identifiant de fichier du code-barres MacroPdf417 (champ requis). Identifiant de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append |
| [setMacroPdf417FileName()](#setmacropdf417filename) | Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append) La taille du fichier |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | Identifiant de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu'à MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | Nombre de segments du code-barres MacroPdf417 (champ optionnel). Nombre de segments du code-barres MicroPDF417 (champ optionnel pour Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | Nom de l'expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l'expéditeur du code-barres MicroPDF417 (champ optionnel pour Structured Append |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PD. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | Horodatage du code-barres MacroPdf417 (champ optionnel). Horodatage du code-barres MicroPDF417 (champ optionnel pour Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Définit le type de symbologie Pdf417 du niveau de correction d’erreur du BarCode allant de level0 à level8, level0 signifie aucune correction d’erreur |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Définit le nom du destinataire du code-barres macro Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Définit la somme de contrôle du code-barres macro Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Définit l’ID de fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Définit le nom de fichier du code-barres macro Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Définit la taille du fichier macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Définit l’ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu’à MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Définit le nombre de segments du code-barres macro Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Définit le nom de l’expéditeur du code-barres macro Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Utilisé pour indiquer à l'encodeur s'il faut ajouter le Terminator Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PD. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Définit l’horodatage du code-barres macro Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). |
| [setReaderInitialization(value)](#setreaderinitialization) | Utilisé pour indiquer au lecteur d’interpréter les données contenues dans le symbole comme une programmation pour l’initialisation du lecteur |
| [setRows()](#setrows) | Nombre de lignes. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Identifie l'ID du code-barres en mode Structured Append de DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres |
| [setTruncate()](#settruncate) | Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. Indicatif de ligne droite |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l’homme de ces Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### getColumns() {#getcolumns}

Nombre de colonnes.

### getECIEncoding() {#geteciencoding}

Identifiants d’interprétation de canal étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L’implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### getEncodeMode() {#getencodemode}

Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

### getErrorLevel() {#geterrorlevel}

Obtient le type de symbologie Pdf417 du niveau de correction d’erreur du BarCode allant de level0 à level8, level0 signifie aucune information de correction d’erreur, level8 signifie la meilleure correction d’erreur, ce qui entraîne une image plus grande.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu’avec MicroPdf417 et encodent les modes 916 et 917 de MicroPdf417. Valeur par défaut : MacroCharacters.None. Ces exemples montrent comment encoder les caractères macro dans MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append)

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de somme de contrôle contient la valeur du CRC 16 bits (2 octets) utilisant le polynôme CCITT-16 : x^16 + x^12 + x^5 + 1.

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de taille de fichier contient la taille en octets du fichier source complet.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu’à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Nombre de segments du code-barres MacroPdf417 (champ optionnel). Nombre de segments du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Nom de l’expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l’expéditeur du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Utilisé pour indiquer à l’encodeur s’il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append)

### getPdf417CompactionMode() {#getpdf417compactionmode}

Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### getPdf417EncodeMode() {#getpdf417encodemode}

Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Obtient le type de symbologie Pdf417 du niveau de correction d’erreur du BarCode allant de level0 à level8, level0 signifie aucune information de correction d’erreur, level8 signifie la meilleure correction d’erreur, ce qui entraîne une image plus grande.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Obtient le nom du destinataire du code-barres macro Pdf417.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Obtient la somme de contrôle du code-barres macro Pdf417.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Obtient l'identifiant de fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Obtient le nom de fichier du code-barres macro Pdf417.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Obtient la taille du fichier macro Pdf417.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Obtient l'identifiant de segment du code-barres macro Pdf417, qui commence à 0, jusqu'à MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Obtient le nombre de segments du code-barres macro Pdf417.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Obtient le nom de l'expéditeur du code-barres macro Pdf417.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Utilisé pour indiquer à l’encodeur s’il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Obtient l'horodatage du code-barres macro Pdf417.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace).

### getRows() {#getrows}

Nombre de lignes.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Identifie l'ID du code-barres DotCode en mode Structured Append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1.

### getTruncate() {#gettruncate}

Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

### isCode128Emulation() {#iscode128emulation}

Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. Ces exemples montrent comment encoder les modes d'émulation Code 128 avec FNC1 en deuxième position et sans. Ainsi, le MicroPdf417 peut être décodé comme un code-barres Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes « Linked » UCC/EAN-128 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. Ces exemples montrent comment encoder les modes « Linked » UCC/EAN-128 dans GS1MicroPdf417 et le drapeau de liaison (918) dans les codes-barres MicroPdf417 et Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Utilisé pour indiquer au lecteur d’interpréter les données contenues dans le symbole comme une programmation pour l’initialisation du lecteur

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### setCode128Emulation() {#setcode128emulation}

Ne peut être utilisé qu'avec MicroPdf417 et encode les modes d'émulation Code 128. Peut encoder FNC1 en deuxième position dans les modes 908 et 909, peut également encoder 910 et 911 qui indiquent simplement que le MicroPdf417 reconnu peut être interprété comme Code 128. Ces exemples montrent comment encoder les modes d'émulation Code 128 avec FNC1 en deuxième position et sans. Ainsi, le MicroPdf417 peut être décodé comme un code-barres Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Nombre de colonnes.

### setECIEncoding() {#seteciencoding}

Identifiants d’interprétation de canal étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. Non appliqué aux champs texte Macro PDF417. L’implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### setEncodeMode() {#setencodemode}

Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

### setErrorLevel(value) {#seterrorlevel}

Définit le niveau de correction d'erreur du type de symbologie Pdf417 du code-barres, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui entraîne une image plus grande.

| Paramètre | Description |
| --- | --- |
| valeur | Niveau de correction d'erreur du type de symbologie Pdf417 du code-barres, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui entraîne une image plus grande. |

### setLinked() {#setlinked}

Définit les modes liés avec les codes-barres GS1MicroPdf417, MicroPdf417 et Pdf417. Avec la symbologie GS1MicroPdf417, encode les modes « Linked » UCC/EAN-128 906, 907, 912, 913, 914, 915. Avec les symbologies MicroPdf417 et Pdf417, encode le drapeau de liaison 918 vers le composant linéaire associé autre qu'un EAN.UCC. Ces exemples montrent comment encoder les modes « Linked » UCC/EAN-128 dans GS1MicroPdf417 et le drapeau de liaison (918) dans les codes-barres MicroPdf417 et Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Les valeurs des caractères macro 05 et 06 sont utilisées pour obtenir un encodage plus compact dans des modes spéciaux. Elles ne peuvent être utilisées qu’avec MicroPdf417 et encodent les modes 916 et 917 de MicroPdf417. Valeur par défaut : MacroCharacters.None. Ces exemples montrent comment encoder les caractères macro dans MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Nom du destinataire du code-barres MacroPdf417 (champ optionnel). Nom du destinataire du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append)

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Somme de contrôle du code-barres MacroPdf417 (champ optionnel). Somme de contrôle du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de somme de contrôle contient la valeur du CRC 16 bits (2 octets) utilisant le polynôme CCITT-16 : x^16 + x^12 + x^5 + 1.

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

ID de fichier du code-barres MacroPdf417 (champ requis). ID de fichier du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Nom de fichier du code-barres MacroPdf417 (champ optionnel). Nom de fichier du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Taille du fichier MacroPdf417 (champ optionnel). Taille du fichier MicroPDF417 (champ optionnel pour le mode Structured Append). Le champ de taille de fichier contient la taille en octets du fichier source complet.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

ID de segment du code-barres MacroPdf417 (champ requis), qui commence à 0, jusqu’à MacroSegmentsCount - 1. ID de segment du code-barres MicroPDF417 (champ requis pour le mode Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Nombre de segments du code-barres MacroPdf417 (champ optionnel). Nombre de segments du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Nom de l’expéditeur du code-barres MacroPdf417 (champ optionnel). Nom de l’expéditeur du code-barres MicroPDF417 (champ optionnel pour le mode Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Utilisé pour indiquer à l’encodeur s’il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Horodatage du code-barres MacroPdf417 (champ facultatif). Horodatage du code-barres MicroPDF417 (champ facultatif pour le mode Structured Append)

### setPdf417CompactionMode() {#setpdf417compactionmode}

Type de symbologie Pdf417 du mode de compaction du code-barres. Valeur par défaut : Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Identifie le mode d'encodage Pdf417. Valeur par défaut : Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Définit le niveau de correction d'erreur du type de symbologie Pdf417 du code-barres, allant de level0 à level8 ; level0 signifie aucune information de correction d'erreur, level8 signifie la meilleure correction d'erreur, ce qui entraîne une image plus grande.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Définit le nom du destinataire du code-barres macro Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Définit la somme de contrôle du code-barres macro Pdf417.

| Paramètre | Description |
| --- | --- |
| valeur | Le champ de somme de contrôle contient la valeur du checksum CRC de 16 bits (2 octets) utilisant le polynôme CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'interprétation de canal étendu. S'applique aux champs texte Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Définit l’ID de fichier du code-barres macro Pdf417. Utilisé pour MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Définit le nom de fichier du code-barres macro Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Définit la taille du fichier macro Pdf417.

| Paramètre | Description |
| --- | --- |
| valeur | Le champ de taille de fichier contient la taille en octets du fichier source complet. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Définit l’ID de segment du code-barres macro Pdf417, qui commence à 0, jusqu’à MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Définit le nombre de segments du code-barres macro Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Définit le nom de l’expéditeur du code-barres macro Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Utilisé pour indiquer à l’encodeur s’il faut ajouter le terminateur Macro PDF417 (codeword 922) au segment. Appliqué uniquement pour Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Définit l’horodatage du code-barres macro Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace).

### setReaderInitialization(value) {#setreaderinitialization}

Utilisé pour indiquer au lecteur d’interpréter les données contenues dans le symbole comme une programmation pour l’initialisation du lecteur

| Paramètre | Description |
| --- | --- |
| valeur |  |

### setRows() {#setrows}

Nombre de lignes.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Identifie l'ID du code-barres DotCode en mode Structured Append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1.

### setTruncate() {#settruncate}

Indique si le type de symbologie Pdf417 du code-barres est tronqué (pour réduire l'espace). Aussi connu sous le nom de CompactPDF417. L'indicateur de ligne droite et le motif d'arrêt droit sont supprimés dans ce mode.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l’homme de ces Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.

---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke une information de métadonnées MacroPdf417 du code-barres reconnu"
type: docs
weight: 760
url: /fr/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Stocke une information de métadonnées MacroPdf417 du code-barres reconnu

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur Pdf417ExtendedParameters spécifiée. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nom du destinataire Macro PDF417 (facultatif). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Somme de contrôle Macro PDF417 (facultatif). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Obtient l'ID de fichier du code-barres, disponible uniquement avec MacroPdf417. Valeur : L'ID de fichier pour MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nom de fichier Macro PDF417 (facultatif). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Taille du fichier Macro PDF417 (facultatif). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Obtient l'ID du segment du code‑barres, uniquement disponible avec MacroPdf417. Valeur : L'ID du segment du code‑barres. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Obtient le nombre de segments du code‑barres macro pdf417. La valeur par défaut est -1. Valeur : Nombre de segments. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nom de l'expéditeur Macro PDF417 (facultatif). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Horodatage Macro PDF417 (facultatif). |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isCode128Emulation()](#iscode128emulation) | Indicateur qui indique que le code‑barres MicroPdf417 est encodé avec les mots‑code d'émulation Code 128 908, 909, 910 ou 911. |
| [isLinked()](#islinked) | Indicateur qui indique que le code‑barres doit être lié à un code‑barres 1D. Valeur : Indicateur de liaison |
| [isReaderInitialization()](#isreaderinitialization) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur Pdf417ExtendedParameters spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nom du destinataire Macro PDF417 (facultatif).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Somme de contrôle Macro PDF417 (facultatif).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Obtient l'ID de fichier du code-barres, disponible uniquement avec MacroPdf417. Valeur : L'ID de fichier pour MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Nom de fichier Macro PDF417 (facultatif).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Taille du fichier Macro PDF417 (facultatif).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Obtient l'ID du segment du code‑barres, uniquement disponible avec MacroPdf417. Valeur : L'ID du segment du code‑barres.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Obtient le nombre de segments du code‑barres macro pdf417. La valeur par défaut est -1. Valeur : Nombre de segments.

### getMacroPdf417Sender() {#getmacropdf417sender}

Nom de l'expéditeur Macro PDF417 (facultatif).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Horodatage Macro PDF417 (facultatif).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Indicateur qui indique que le code‑barres MicroPdf417 est encodé avec les mots‑code d'émulation Code 128 908, 909, 910 ou 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Indicateur qui indique que le code‑barres doit être lié à un code‑barres 1D. Valeur : Indicateur de liaison

### isReaderInitialization() {#isreaderinitialization}

Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

**Returns:** Reader initialization flag

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.

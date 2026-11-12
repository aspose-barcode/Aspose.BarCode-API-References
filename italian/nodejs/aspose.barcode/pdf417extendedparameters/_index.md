---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto"
type: docs
weight: 760
url: /it/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Memorizza informazioni di metadati MacroPdf417 del codice a barre riconosciuto

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore Pdf417ExtendedParameters specificato. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Nome del destinatario Macro PDF417 (opzionale). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Checksum Macro PDF417 (opzionale). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417. Valore: L'ID file per MacroPdf417 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Nome file Macro PDF417 (opzionale). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Dimensione file Macro PDF417 (opzionale). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | Restituisce l'ID segmento del codice a barre, disponibile solo con MacroPdf417. Valore: L'ID segmento del codice a barre. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | Restituisce il conteggio dei segmenti del codice a barre macro pdf417. Il valore predefinito è -1. Valore: Conteggio segmenti. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Nome del mittente Macro PDF417 (opzionale). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Marca temporale Macro PDF417 (opzionale). |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isCode128Emulation()](#iscode128emulation) | Flag che indica che il codice a barre MicroPdf417 è codificato con i codici di emulazione Code 128 908, 909, 910 o 911. |
| [isLinked()](#islinked) | Flag che indica che il codice a barre deve essere collegato a un codice a barre 1D. Valore: Flag di collegamento |
| [isReaderInitialization()](#isreaderinitialization) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo Pdf417ExtendedParameters. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore Pdf417ExtendedParameters specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Nome del destinatario Macro PDF417 (opzionale).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Checksum Macro PDF417 (opzionale).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Ottiene l'ID file del codice a barre, disponibile solo con MacroPdf417. Valore: L'ID file per MacroPdf417

### getMacroPdf417FileName() {#getmacropdf417filename}

Nome file Macro PDF417 (opzionale).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Dimensione file Macro PDF417 (opzionale).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Restituisce l'ID segmento del codice a barre, disponibile solo con MacroPdf417. Valore: L'ID segmento del codice a barre.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Restituisce il conteggio dei segmenti del codice a barre macro pdf417. Il valore predefinito è -1. Valore: Conteggio segmenti.

### getMacroPdf417Sender() {#getmacropdf417sender}

Nome del mittente Macro PDF417 (opzionale).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Marca temporale Macro PDF417 (opzionale).

**Returns:** Time stamp.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

Flag che indica che il codice a barre MicroPdf417 è codificato con i codici di emulazione Code 128 908, 909, 910 o 911.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

Flag che indica che il codice a barre deve essere collegato a un codice a barre 1D. Valore: Flag di collegamento

### isReaderInitialization() {#isreaderinitialization}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

**Returns:** Reader initialization flag

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo Pdf417ExtendedParameters.

**Returns:** A string that represents this Pdf417ExtendedParameters.

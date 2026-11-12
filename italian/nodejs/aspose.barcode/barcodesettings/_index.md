---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "I principali parametri di decodifica BarCode."
type: docs
weight: 150
url: /it/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti.

```js
new BarcodeSettings(settings)
```

Costruttore di copia BarcodeSettings

| Parametro | Descrizione |
| --- | --- |
| impostazioni | L'origine dei dati |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Ottiene i parametri di decodifica AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie whic |
| [getDetectEncoding()](#getdetectencoding) | Il flag che forza il motore a rilevare la codifica del testo del codice per i set di caratteri Unicode. Il valore predefinito è true. |
| [getStripFNC()](#getstripfnc) | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie whic |
| [setDetectEncoding()](#setdetectencoding) | Il flag che forza il motore a rilevare la codifica del testo del codice per i set di caratteri Unicode. Il valore predefinito è true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o |
| [setStripFNC(value)](#setstripfnc) | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. |

### getAustraliaPost() {#getaustraliapost}

Ottiene i parametri di decodifica AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale. Checksum mai usato: Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum sempre usato: le restanti simbologie.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Il flag che forza il motore a rilevare la codifica del testo del codice per i set di caratteri Unicode. Il valore predefinito è true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false. Esempio: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale. Checksum mai usato: Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum sempre usato: le restanti simbologie.

| Parametro | Descrizione |
| --- | --- |
| valore | Abilita la convalida del checksum durante il riconoscimento per i codici a barre 1D e postali. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Il flag che forza il motore a rilevare la codifica del testo del codice per i set di caratteri Unicode. Il valore predefinito è true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Restituisce solo i tipi di codice a barre specificati esplicitamente per il riconoscimento. Quando abilitato, i codici a barre riconosciuti di altri tipi compatibili o equivalenti vengono filtrati. Il valore predefinito è false. Esempio: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false.

| Parametro | Descrizione |
| --- | --- |
| valore | Rimuovi i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

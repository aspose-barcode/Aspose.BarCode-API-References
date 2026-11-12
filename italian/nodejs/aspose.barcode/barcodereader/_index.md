---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre."
type: docs
weight: 90
url: /it/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader incapsula un'immagine che può contenere uno o più codici a barre, quindi può eseguire l'operazione ReadBarCodes per rilevare i codici a barre.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Inizializza una nuova istanza di BarCodeReader

| Parametro | Descrizione |
| --- | --- |
| immagine | codificato come stringa base64 o percorso dell'immagine |
| aree | array di oggetti di tipo Rectangle |
| decodeTypes | l'array di oggetti per DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Esporta le proprietà BarCode nel file xml specificato |
| [containsAny()](#containsany) | Determina se uno dei tipi di decodifica forniti è incluso in |
| [exportToXml(xmlFile)](#exporttoxml) | Esporta le proprietà BarCode nel file xml specificato |
| [getBarCodeReadType()](#getbarcodereadtype) | Ottiene il tipo di decodifica del codice a barre di input |
| [getBarcodeSettings()](#getbarcodesettings) | I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti. |
| [getFoundBarCodes()](#getfoundbarcodes) | Ottiene l'array BarCodeResult riconosciuto |
| [getFoundCount()](#getfoundcount) | Ottiene il conteggio dei codici a barre riconosciuti |
| [getQualitySettings()](#getqualitysettings) | QualitySettings consente di configurare manualmente la qualità e la velocità di riconoscimento. Puoi impostare rapidamente QualitySettings tramite em |
| [getTimeout()](#gettimeout) | Ottiene il timeout del processo di riconoscimento in millisecondi. |
| [readBarCodes()](#readbarcodes) | Legge BarCodeResult dall'immagine. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Imposta l'immagine bitmap e le aree per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Imposta l'array di tipo SingleDecodeType per il riconoscimento. Deve essere chiamato prima del metodo readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings consente di configurare manualmente la qualità e la velocità di riconoscimento. Puoi impostare rapidamente QualitySettings tramite em |
| [setTimeout(value)](#settimeout) | Imposta il timeout del processo di riconoscimento in millisecondi. |

### importFromXml(xmlFile) (static) {#importfromxml}

Esporta le proprietà BarCode nel file xml specificato

| Parametro | Descrizione |
| --- | --- |
| xmlFile | Il nome del file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Determina se uno dei tipi di decodifica forniti è incluso in

| Parametro | Descrizione |
| --- | --- |
| ...decodeTypes | Tipi da verificare. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Esporta le proprietà BarCode nel file xml specificato

| Parametro | Descrizione |
| --- | --- |
| xmlFile | Il nome del file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Ottiene il tipo di decodifica del codice a barre di input

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

I principali parametri di decodifica BarCode. Contiene parametri che influenzano i dati riconosciuti.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Ottiene l'array BarCodeResult riconosciuto

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Ottiene il conteggio dei codici a barre riconosciuti

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Ottiene il timeout del processo di riconoscimento in millisecondi.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Legge BarCodeResult dall'immagine.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Imposta l'immagine bitmap e le aree per il riconoscimento. Deve essere chiamato prima del metodo ReadBarCodes().

| Parametro | Descrizione |
| --- | --- |
| imageResource | L'immagine per il riconoscimento. |
| aree | elenco delle aree per il riconoscimento |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Imposta l'array di tipo SingleDecodeType per il riconoscimento. Deve essere chiamato prima del metodo readBarCodes().

| Parametro | Descrizione |
| --- | --- |
| tipi | L'array di tipo SingleDecodeType da leggere. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

Imposta il timeout del processo di riconoscimento in millisecondi.

| Parametro | Descrizione |
| --- | --- |
| valore | Il timeout. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

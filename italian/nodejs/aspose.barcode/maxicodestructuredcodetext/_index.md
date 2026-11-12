---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3."
type: docs
weight: 700
url: /it/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato. |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [getCountryCode()](#getcountrycode) | Identifica il codice paese a 3 cifre. |
| [getHashCode()](#gethashcode) | Restituisce il codice hash per questa istanza. |
| [getPostalCode()](#getpostalcode) | Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3. |
| [getSecondMessage()](#getsecondmessage) | Identifica il secondo messaggio del codice a barre. |
| [getServiceCategory()](#getservicecategory) | Identifica la categoria di servizio a 3 cifre. |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setCountryCode()](#setcountrycode) | Identifica il codice paese a 3 cifre. |
| [setPostalCode()](#setpostalcode) | Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3. |
| [setSecondMessage()](#setsecondmessage) | Identifica il secondo messaggio del codice a barre. |
| [setServiceCategory()](#setservicecategory) | Identifica la categoria di servizio a 3 cifre. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore da confrontare con questa istanza |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identifica il codice paese a 3 cifre.

### getHashCode() {#gethashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3.

### getSecondMessage() {#getsecondmessage}

Identifica il secondo messaggio del codice a barre.

### getServiceCategory() {#getservicecategory}

Identifica la categoria di servizio a 3 cifre.

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setCountryCode() {#setcountrycode}

Identifica il codice paese a 3 cifre.

### setPostalCode() {#setpostalcode}

Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3.

### setSecondMessage() {#setsecondmessage}

Identifica il secondo messaggio del codice a barre.

### setServiceCategory() {#setservicecategory}

Identifica la categoria di servizio a 3 cifre.

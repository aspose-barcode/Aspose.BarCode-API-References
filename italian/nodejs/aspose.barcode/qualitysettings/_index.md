---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento."
type: docs
weight: 860
url: /it/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings consente di configurare manualmente la qualità e la velocità del riconoscimento. È possibile impostare rapidamente QualitySettings tramite i preset incorporati: HighPerformance, NormalQuality, HighQuality, MaxBarCodes oppure configurare manualmente le opzioni separate. Il valore predefinito di QualitySettings è NormalQuality.

```js
new QualitySettings()
```

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità. |
| [getHighQuality()](#gethighquality) *(static)* | Preset di qualità di riconoscimento HighQuality. Questo preset è sviluppato per codici a barre di bassa qualità. |
| [getMaxQuality()](#getmaxquality) *(static)* | Preset di qualità di riconoscimento MaxQuality. Questo preset è sviluppato per riconoscere tutti i possibili codici a barre, anche quelli errati. |
| [getNormalQuality()](#getnormalquality) *(static)* | Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Consente al motore di riconoscere i codici a barre con checksum o valori errati. La modalità può essere usata per riconoscere codici danneggiati |
| [getBarcodeQuality()](#getbarcodequality) | Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Elemento del codice a barre con qualità inferiore r |
| [getComplexBackground()](#getcomplexbackground) | Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori. |
| [getDeconvolution()](#getdeconvolution) | Modalità deconvoluzione (restauro immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione |
| [getInverseImage()](#getinverseimage) | Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza). |
| [getMinimalXDimension()](#getminimalxdimension) | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Consente al motore di riconoscere i codici a barre con checksum o valori errati. La modalità può essere usata per riconoscere codici danneggiati |
| [setBarcodeQuality(value)](#setbarcodequality) | Modalità che consente ai metodi di riconoscere gli elementi del codice a barre con la qualità selezionata. Elemento del codice a barre con qualità inferiore r |
| [setComplexBackground(value)](#setcomplexbackground) | Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori. |
| [setDeconvolution(value)](#setdeconvolution) | Modalità deconvoluzione (restauro immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione |
| [setInverseImage(value)](#setinverseimage) | Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |

### getHighPerformance() (static) {#gethighperformance}

Preset di qualità di riconoscimento HighPerformance. I codici a barre di alta qualità sono riconosciuti correttamente in questa modalità.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Preset di qualità di riconoscimento HighQuality. Questo preset è sviluppato per codici a barre di bassa qualità.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Preset di qualità di riconoscimento MaxQuality. Questo preset è stato sviluppato per riconoscere tutti i possibili codici a barre, anche quelli errati. Questo esempio mostra come utilizzare la modalità MaxQuality reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Valore: preset di qualità di riconoscimento MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Preset di qualità di riconoscimento NormalQuality. Adatto per la maggior parte dei codici a barre

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Consente al motore di riconoscere i codici a barre con checksum errato o valori non corretti. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Modalità di deconvoluzione (restauro delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale, come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione che corrode l'immagine, dobbiamo verificare le funzioni più conosciute, come la nitidezza o la morfologia matematica.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Consente al motore di riconoscere i codici a barre con checksum errato o valori non corretti. La modalità può essere usata per riconoscere codici a barre danneggiati con testo errato.

| Parametro | Descrizione |
| --- | --- |
| valore | Consente al motore di riconoscere codici a barre errati. |

### setBarcodeQuality(value) {#setbarcodequality}

Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. Un elemento del codice a barre con qualità inferiore richiede metodi più complessi, rallentando il riconoscimento.

| Parametro | Descrizione |
| --- | --- |
| valore | Modalità che abilita i metodi per riconoscere gli elementi del codice a barre con la qualità selezionata. |

### setComplexBackground(value) {#setcomplexbackground}

Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori.

| Parametro | Descrizione |
| --- | --- |
| valore | Riconoscimento aggiuntivo dei codici a barre a colori su immagini a colori. |

### setDeconvolution(value) {#setdeconvolution}

Modalità di deconvoluzione (restauro delle immagini) che definisce il livello di degradazione dell'immagine. Originariamente la deconvoluzione è una funzione che può ripristinare un'immagine degradata (convoluta) da qualsiasi funzione naturale, come la sfocatura, durante l'acquisizione dell'immagine con la fotocamera. Poiché non possiamo rilevare la funzione che corrode l'immagine, dobbiamo verificare le funzioni più conosciute, come la nitidezza o la morfologia matematica.

| Parametro | Descrizione |
| --- | --- |
| valore | Modalità di deconvoluzione che definisce il livello di degradazione dell'immagine. |

### setInverseImage(value) {#setinverseimage}

Modalità che abilita o disabilita il riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti (luminanza).

| Parametro | Descrizione |
| --- | --- |
| valore | Riconoscimento aggiuntivo dei codici a barre su immagini con colori invertiti |

### setMinimalXDimension(value) {#setminimalxdimension}

Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension.

| Parametro | Descrizione |
| --- | --- |
| valore | Dimensione minima di XDimension in pixel, utilizzata con UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Modalità di riconoscimento che imposta la dimensione (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra.

| Parametro | Descrizione |
| --- | --- |
| valore | (da 1 all'infinito) dell'elemento minimo del codice a barre: cella della matrice o barra. |

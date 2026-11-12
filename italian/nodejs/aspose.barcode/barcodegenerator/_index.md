---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "BarcodeGenerator per la generazione di immagini di codici a barre lato server."
type: docs
weight: 130
url: /it/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator per la generazione di immagini di codici a barre lato server. Simbologie supportate: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Costruttore BarcodeGenerator.

| Parametro | Descrizione |
| --- | --- |
| encodeType | Tipo di simbologia del codice a barre. Usa la classe EncodeTypes per configurare una simbologia. |
| codeText | Testo da codificare. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importa le proprietà BarCode dal file XML specificato e crea un'istanza di BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Esporta le proprietà BarCode nel file XML specificato. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Genera l'immagine del codice a barre con le impostazioni correnti. Questo esempio mostra come creare e salvare un'immagine di codice a barre. |
| [getBarcodeType()](#getbarcodetype) | Tipo di simbologia del codice a barre. |
| [getCodeText()](#getcodetext) | Testo da codificare. |
| [getParameters()](#getparameters) | Parametri di generazione. |
| [save(filePath, format)](#save) | Salva l'immagine del codice a barre in un file specifico in un formato specifico. |
| [setBarcodeType()](#setbarcodetype) | Tipo di simbologia del codice a barre. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Codifica il testo Unicode `codeText ` in una sequenza di byte usando la `encoding ` specificata. UTF-8 è il più comunemente usato en |

### importFromXml(filePath) (static) {#importfromxml}

Importa le proprietà BarCode dal file XML specificato e crea un'istanza di BarcodeGenerator.

| Parametro | Descrizione |
| --- | --- |
| filePath | Il nome del file |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Esporta le proprietà BarCode nel file XML specificato.

| Parametro | Descrizione |
| --- | --- |
| filePath | Il file xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Genera l'immagine del codice a barre con le impostazioni correnti. Questo esempio mostra come creare e salvare un'immagine di codice a barre.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formato | BarCodeImageFormat | Valore BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Tipo di simbologia del codice a barre.

### getCodeText() {#getcodetext}

Testo da codificare.

### getParameters() {#getparameters}

Parametri di generazione.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Salva l'immagine del codice a barre in un file specifico in un formato specifico.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso in cui salvare. |
| formato | BarCodeImageFormat | Valore BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Tipo di simbologia del codice a barre.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Codifica il testo Unicode `codeText ` in una sequenza di byte usando la `encoding ` specificata. UTF-8 è la codifica più comunemente usata. Se la codifica lo supporta e `insertBOM ` è impostato su `true`, la funzione include un `byte order mark (BOM) `. Questa funzione è destinata all'uso solo con codici a barre 2D (ad es., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, ecc.). Consente la codifica manuale del testo Unicode usando codifiche nazionali o speciali; tuttavia, questo metodo è considerato obsoleto nelle applicazioni moderne. Per casi d'uso moderni, si raccomanda la codifica `ECI ` per i dati Unicode. L'uso di questa funzione con codici a barre 1D, codici a barre conformi a GS1 (inclusi i 2D) o codici a barre HIBC (inclusi i 2D) non è supportato dagli standard dei codici a barre corrispondenti e può portare a risultati imprevedibili. Questo esempio mostra come utilizzare `SetCodeText` con o senza BOM per i codici a barre 2D. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parametro | Descrizione |
| --- | --- |
| codeText | Stringa CodeText |
| codifica | Codifica applicata |
| insertBOM | Indica se inserire un byte order mark (BOM) quando la codifica specificata lo supporta (ad es., UTF-8, UTF-16, UTF-32). Se impostato su `true`, il BOM viene aggiunto; se `false`, il BOM viene omesso anche se la codifica normalmente lo utilizza. |

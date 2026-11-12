---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "BarcodeGenerator voor het genereren van barcode‑afbeeldingen op de backend."
type: docs
weight: 130
url: /nl/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator voor het genereren van barcode‑afbeeldingen op de backend. ondersteunde symbologieën: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR‑code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator‑constructor.

| Parameter | Beschrijving |
| --- | --- |
| encodeType | Barcode‑symbologie‑type. Gebruik de EncodeTypes‑klasse om een symbologie in te stellen. |
| codeText | Te coderen tekst. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importeert BarCode‑eigenschappen uit het opgegeven xml‑bestand en maakt een BarcodeGenerator‑instantie aan. |
| [exportToXml(filePath)](#exporttoxml) | Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Genereer de barcode‑afbeelding met de huidige instellingen. Dit voorbeeld toont hoe een barcode‑afbeelding te maken en op te slaan. |
| [getBarcodeType()](#getbarcodetype) | Barcode‑symbologie‑type. |
| [getCodeText()](#getcodetext) | Te coderen tekst. |
| [getParameters()](#getparameters) | Generatie‑parameters. |
| [save(filePath, format)](#save) | Sla de barcode‑afbeelding op naar een specifiek bestand in een specifiek formaat. |
| [setBarcodeType()](#setbarcodetype) | Barcode‑symbologie‑type. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Encodeert de Unicode `codeText ` naar een byte‑reeks met de opgegeven `encoding `. UTF-8 is de meest gebruikte en |

### importFromXml(filePath) (static) {#importfromxml}

Importeert BarCode‑eigenschappen uit het opgegeven xml‑bestand en maakt een BarcodeGenerator‑instantie aan.

| Parameter | Beschrijving |
| --- | --- |
| filePath | De naam van het bestand |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exporteert BarCode‑eigenschappen naar het opgegeven xml‑bestand.

| Parameter | Beschrijving |
| --- | --- |
| filePath | Het xml‑bestand |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Genereer de barcode‑afbeelding met de huidige instellingen. Dit voorbeeld toont hoe een barcode‑afbeelding te maken en op te slaan.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formaat | BarCodeImageFormat | BarCodeImageFormat‑waarde (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Barcode‑symbologie‑type.

### getCodeText() {#getcodetext}

Te coderen tekst.

### getParameters() {#getparameters}

Generatie‑parameters.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Sla de barcode‑afbeelding op naar een specifiek bestand in een specifiek formaat.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Pad om op te slaan. |
| formaat | BarCodeImageFormat | BarCodeImageFormat‑waarde (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Barcode‑symbologie‑type.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Encodeert de Unicode `codeText ` naar een byte‑reeks met de opgegeven `encoding `. UTF-8 is de meest gebruikte codering. Als de codering dit ondersteunt en `insertBOM ` is ingesteld op `true`, voegt de functie een `byte order mark (BOM) ` toe. Deze functie is alleen bedoeld voor gebruik met 2D‑barcodes (bijv. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, enz.). Het maakt handmatige codering van Unicode‑tekst mogelijk met nationale of speciale coderingen; echter, deze methode wordt als verouderd beschouwd in moderne toepassingen. Voor moderne scenario's wordt `ECI `‑codering aanbevolen voor Unicode‑gegevens. Het gebruik van deze functie met 1D‑barcodes, GS1‑conforme barcodes (inclusief 2D), of HIBC‑barcodes (inclusief 2D) wordt niet ondersteund door de bijbehorende barcode‑standaarden en kan leiden tot onvoorspelbare resultaten. Dit voorbeeld toont hoe `SetCodeText` te gebruiken met of zonder een BOM voor 2D‑barcodes. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parameter | Beschrijving |
| --- | --- |
| codeText | CodeText‑string |
| codering | Toegepaste codering |
| insertBOM | Geeft aan of een byte order mark (BOM) moet worden ingevoegd wanneer de opgegeven codering dit ondersteunt (bijv. UTF-8, UTF-16, UTF-32). Als ingesteld op `true`, wordt de BOM toegevoegd; als `false`, wordt de BOM weggelaten, zelfs als de codering normaal gesproken er een gebruikt. |

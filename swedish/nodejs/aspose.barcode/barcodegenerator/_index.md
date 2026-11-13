---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "BarcodeGenerator för generering av streckkodsbilder i backend."
type: docs
weight: 130
url: /sv/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator för generering av streckkodsbilder i backend. stödda symboler: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator-konstruktor.

| Parameter | Beskrivning |
| --- | --- |
| encodeType | Streckkodssymboltyp. Använd EncodeTypes-klassen för att konfigurera en symbol. |
| codeText | Text att koda. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importerar BarCode-egenskaper från den angivna XML-filen och skapar ett BarcodeGenerator-objekt. |
| [exportToXml(filePath)](#exporttoxml) | Exporterar BarCode-egenskaper till den angivna XML-filen. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Generera streckkodsbilden med aktuella inställningar. Detta exempel visar hur man skapar och sparar en streckkodsbild. |
| [getBarcodeType()](#getbarcodetype) | Streckkodssymboltyp. |
| [getCodeText()](#getcodetext) | Text att koda. |
| [getParameters()](#getparameters) | Genereringsparametrar. |
| [save(filePath, format)](#save) | Spara streckkodsbilden till en specifik fil i ett specifikt format. |
| [setBarcodeType()](#setbarcodetype) | Streckkodssymboltyp. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Kodar Unicode `codeText ` till en byte-sekvens med den angivna `encoding `. UTF-8 är den mest använda |

### importFromXml(filePath) (static) {#importfromxml}

Importerar BarCode-egenskaper från den angivna XML-filen och skapar ett BarcodeGenerator-objekt.

| Parameter | Beskrivning |
| --- | --- |
| filePath | Filens namn |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exporterar BarCode-egenskaper till den angivna XML-filen.

| Parameter | Beskrivning |
| --- | --- |
| filePath | XML-filen |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Generera streckkodsbilden med aktuella inställningar. Detta exempel visar hur man skapar och sparar en streckkodsbild.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | BarCodeImageFormat | BarCodeImageFormat-värde (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Streckkodssymboltyp.

### getCodeText() {#getcodetext}

Text att koda.

### getParameters() {#getparameters}

Genereringsparametrar.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Spara streckkodsbilden till en specifik fil i ett specifikt format.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökväg att spara till. |
| format | BarCodeImageFormat | BarCodeImageFormat-värde (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Streckkodssymboltyp.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Kodar Unicode `codeText ` till en byte-sekvens med den angivna `encoding`. UTF-8 är den mest använda kodningen. Om kodningen stödjer det och `insertBOM ` är satt till `true`, inkluderar funktionen ett `byte order mark (BOM) `. Denna funktion är avsedd endast för 2D-streckkoder (t.ex. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR osv.). Den möjliggör manuell kodning av Unicode‑text med nationella eller speciella kodningar; dock anses denna metod föråldrad i moderna applikationer. För moderna användningsfall rekommenderas `ECI `-kodning för Unicode‑data. Att använda denna funktion med 1D-streckkoder, GS1‑kompatibla streckkoder (inklusive 2D) eller HIBC‑streckkoder (inklusive 2D) stöds inte av motsvarande streckkodstandarder och kan leda till oförutsägbara resultat. Detta exempel visar hur man använder `SetCodeText` med eller utan ett BOM för 2D-streckkoder.
//Encode codetext using UTF-8 with BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText("車種名", "UTF-8", true);
gen.save("barcode.png", BarCodeImageFormat.PNG);
let reader = new BarCodeReader("barcode.png", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log("BarCode CodeText: " + result.getCodeText());
}
//Encode codetext using UTF-8 without BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText("車種名", "UTF-8", false);
gen.save("barcode.png", BarCodeImageFormat.PNG);
let reader = new BarCodeReader("barcode.png", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log("BarCode CodeText: " + result.getCodeText());
}

| Parameter | Beskrivning |
| --- | --- |
| codeText | CodeText-sträng |
| kodning | Tillämpad kodning |
| insertBOM | Anger om ett byte order mark (BOM) ska infogas när den angivna kodningen stödjer det (t.ex. UTF-8, UTF-16, UTF-32). Om satt till `true` läggs BOM till; om `false` utelämnas BOM även om kodningen normalt använder ett. |

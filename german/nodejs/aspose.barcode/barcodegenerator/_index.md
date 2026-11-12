---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "BarcodeGenerator zur Erzeugung von Barcode‑Bildern im Backend."
type: docs
weight: 130
url: /de/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator zur Erzeugung von Barcode‑Bildern im Backend. Unterstützte Symbologien: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended, Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet, EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR‑Code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator‑Konstruktor.

| Parameter | Beschreibung |
| --- | --- |
| encodeType | Barcode‑Symbologie‑Typ. Verwenden Sie die EncodeTypes‑Klasse, um eine Symbologie einzurichten. |
| codeText | Zu kodierender Text. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und erstellt eine BarcodeGenerator‑Instanz. |
| [exportToXml(filePath)](#exporttoxml) | Exportiert BarCode‑Eigenschaften in die angegebene XML‑Datei. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Erzeugt das Barcode‑Bild mit den aktuellen Einstellungen. Dieses Beispiel zeigt, wie ein Barcode‑Bild erstellt und gespeichert wird. |
| [getBarcodeType()](#getbarcodetype) | Barcode‑Symbologie‑Typ. |
| [getCodeText()](#getcodetext) | Zu kodierender Text. |
| [getParameters()](#getparameters) | Erzeugungsparameter. |
| [save(filePath, format)](#save) | Speichert das Barcode‑Bild in einer bestimmten Datei in einem bestimmten Format. |
| [setBarcodeType()](#setbarcodetype) | Barcode‑Symbologie‑Typ. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Kodiert den Unicode `codeText ` in eine Bytefolge unter Verwendung der angegebenen `encoding `. UTF-8 ist die am häufigsten verwendete en |

### importFromXml(filePath) (static) {#importfromxml}

Importiert BarCode‑Eigenschaften aus der angegebenen XML‑Datei und erstellt eine BarcodeGenerator‑Instanz.

| Parameter | Beschreibung |
| --- | --- |
| filePath | Der Name der Datei |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exportiert BarCode‑Eigenschaften in die angegebene XML‑Datei.

| Parameter | Beschreibung |
| --- | --- |
| filePath | Die xml-Datei |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Erzeugt das Barcode‑Bild mit den aktuellen Einstellungen. Dieses Beispiel zeigt, wie ein Barcode‑Bild erstellt und gespeichert wird.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | BarCodeImageFormat | BarCodeImageFormat-Wert (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Barcode‑Symbologie‑Typ.

### getCodeText() {#getcodetext}

Zu kodierender Text.

### getParameters() {#getparameters}

Erzeugungsparameter.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Speichert das Barcode‑Bild in einer bestimmten Datei in einem bestimmten Format.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Pfad zum Speichern. |
| format | BarCodeImageFormat | BarCodeImageFormat-Wert (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Barcode‑Symbologie‑Typ.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Kodiert den Unicode `codeText ` in eine Bytefolge unter Verwendung der angegebenen `encoding `. UTF-8 ist die am häufigsten verwendete Kodierung. Wenn die Kodierung dies unterstützt und `insertBOM ` auf `true` gesetzt ist, fügt die Funktion ein `byte order mark (BOM) ` ein. Diese Funktion ist ausschließlich für die Verwendung mit 2D-Barcodes vorgesehen (z. B. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR usw.). Sie ermöglicht die manuelle Kodierung von Unicode-Text mit nationalen oder speziellen Kodierungen; diese Methode gilt jedoch in modernen Anwendungen als veraltet. Für aktuelle Anwendungsfälle wird die `ECI `‑Kodierung für Unicode‑Daten empfohlen. Die Verwendung dieser Funktion mit 1D‑Barcodes, GS1‑konformen Barcodes (einschließlich 2D) oder HIBC‑Barcodes (einschließlich 2D) wird von den entsprechenden Barcode‑Standards nicht unterstützt und kann zu unvorhersehbaren Ergebnissen führen. Dieses Beispiel zeigt, wie `SetCodeText` mit oder ohne BOM für 2D‑Barcodes verwendet wird. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parameter | Beschreibung |
| --- | --- |
| codeText | CodeText‑Zeichenfolge |
| Kodierung | Angewandte Kodierung |
| insertBOM | Gibt an, ob ein Byte Order Mark (BOM) eingefügt werden soll, wenn die angegebene Kodierung dies unterstützt (z. B. UTF-8, UTF-16, UTF-32). Ist sie auf `true` gesetzt, wird das BOM hinzugefügt; ist sie auf `false` gesetzt, wird das BOM weggelassen, selbst wenn die Kodierung normalerweise eines verwendet. |

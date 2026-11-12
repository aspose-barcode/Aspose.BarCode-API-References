---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert erkannte Strichcode-Daten wie SingleDecodeType type, `string` codetext, BarCodeRegionParameters region und andere Parameter."
type: docs
weight: 110
url: /de/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Speichert erkannte Strichcode-Daten wie SingleDecodeType type, `string` codetext, BarCodeRegionParameters region und andere Parameter.

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [deepClone()](#deepclone) | Erstellt eine Kopie der Klasse BarCodeResult. |
| [equals(other)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeResult-Wert gleich ist. |
| [getCodeBytes()](#getcodebytes) | Liest die codierten Code-Bytes. Wert: Die Code-Bytes des Strichcodes. |
| [getCodeText(encoding)](#getcodetext) | Liest den Code-Text mit Kodierung. Dieses Beispiel zeigt, wie man `getCodeText` verwendet: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Liest den Strichcode-Typ. Wert: Die Typinformation des erkannten Strichcodes. |
| [getCodeTypeName()](#getcodetypename) | Liest den Namen des Strichcode-Typs. Wert: Der Typname des erkannten Strichcodes. |
| [getConfidence()](#getconfidence) | Liest das Erkennungs‑Vertrauensniveau des erkannten Strichcodes. Wert: BarCodeConfidence.Strong enthält keine Fälschungen oder Fehlinterpretationen. |
| [getExtended()](#getextended) | Liest erweiterte Parameter des erkannten Strichcodes. Wert: Die erweiterten Parameter des erkannten Strichcodes. |
| [getReadingQuality()](#getreadingquality) | Liest die Lesegenauigkeit. Funktioniert für 1D‑ und Post‑Strichcodes. Wert: Der Prozentsatz der Lesegenauigkeit. |
| [getRegion()](#getregion) | Liest den Strichcode‑Bereich. Wert: Der Bereich des erkannten Strichcodes. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeResult zurück. |

### deepClone() {#deepclone}

Erstellt eine Kopie der Klasse BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeResult-Wert gleich ist.

| Parameter | Beschreibung |
| --- | --- |
| andere | Ein BarCodeResult-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Liest die codierten Code-Bytes. Wert: Die Code-Bytes des Strichcodes.

### getCodeText(encoding) {#getcodetext}

Liest den Code-Text mit Kodierung. Dieses Beispiel zeigt, wie man `getCodeText` verwendet: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parameter | Beschreibung |
| --- | --- |
| Kodierung | Die Kodierung für den Codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Liest den Strichcode-Typ. Wert: Die Typinformation des erkannten Strichcodes.

### getCodeTypeName() {#getcodetypename}

Liest den Namen des Strichcode-Typs. Wert: Der Typname des erkannten Strichcodes.

### getConfidence() {#getconfidence}

Liest das Erkennungs‑Vertrauensniveau des erkannten Strichcodes. Wert: BarCodeConfidence.Strong enthält keine Fälschungen oder Fehlinterpretationen, BarCodeConfidence.Moderate kann gelegentlich Fälschungen oder falschen Codetext aufweisen, weil dieses Vertrauensniveau bei Strichcodes mit schwacher Prüfsumme oder ohne Prüfsumme verwendet wird, BarCodeConfidence.NONE hat stets falschen Codetext und kann falsche Erkennungen sein.

### getExtended() {#getextended}

Liest erweiterte Parameter des erkannten Strichcodes. Wert: Die erweiterten Parameter des erkannten Strichcodes.

### getReadingQuality() {#getreadingquality}

Liest die Lesegenauigkeit. Funktioniert für 1D‑ und Post‑Strichcodes. Wert: Der Prozentsatz der Lesegenauigkeit.

### getRegion() {#getregion}

Liest den Strichcode‑Bereich. Wert: Der Bereich des erkannten Strichcodes.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeResult zurück.

**Returns:** A string that represents this BarCodeResult.

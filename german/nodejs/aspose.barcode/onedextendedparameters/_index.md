---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert spezielle Daten eines erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme."
type: docs
weight: 720
url: /de/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Speichert spezielle Daten eines erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen OneDExtendedParameters-Wert entspricht. |
| [getCheckSum()](#getchecksum) | Liest die Prüfsumme für 1D-Barcodes. Wert: Die Prüfsumme für den 1D-Barcode. |
| [getValue()](#getvalue) | Liest den Codetext von 1D-Barcodes ohne Prüfsumme. Wert: Der Codetext von 1D-Barcodes ohne Prüfsumme. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isEmpty()](#isempty) | Prüft, ob alle Parameter nur Standardwerte haben. Wert: Gibt `true ` zurück, wenn alle Parameter nur Standardwerte haben; o |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses OneDExtendedParameters zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen OneDExtendedParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Liest die Prüfsumme für 1D-Barcodes. Wert: Die Prüfsumme für den 1D-Barcode.

### getValue() {#getvalue}

Liest den Codetext von 1D-Barcodes ohne Prüfsumme. Wert: Der Codetext von 1D-Barcodes ohne Prüfsumme.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Prüft, ob alle Parameter nur Standardwerte haben. Wert: Gibt `true ` zurück, wenn alle Parameter nur Standardwerte haben; andernfalls `false `.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses OneDExtendedParameters zurück.

**Returns:** A string that represents this OneDExtendedParameters.

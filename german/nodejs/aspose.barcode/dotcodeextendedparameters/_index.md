---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert spezielle Daten des erkannten DotCode-Barcodes. Dieses Beispiel zeigt, wie man rohe DotCode-Werte erhält"
type: docs
weight: 380
url: /de/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Speichert spezielle Daten des erkannten DotCode-Barcodes. Dieses Beispiel zeigt, wie man rohe DotCode-Werte erhält

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `DotCodeExtendedParameters`-Wert entspricht. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Ermittelt die ID des DotCode Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Ermittelt die Anzahl der DotCode Structured Append Mode Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. Wert: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Ermittelt die ID des DotCode Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Ermittelt die Anzahl der DotCode Structured Append Mode Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. Wert: |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isReaderInitialization()](#isreaderinitialization) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DotCodeExtendedParameters` zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `DotCodeExtendedParameters`-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. Standardwert ist false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Ermittelt die ID des DotCode Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Standardwert ist -1. Wert: Die ID des DotCode Structured Append Mode Barcodes.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Ermittelt die Anzahl der DotCode Structured Append Mode Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. Wert: Die Anzahl des DotCode Structured Append Mode Barcodes.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Ermittelt die ID des DotCode Structured Append Mode Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode-Anzahl sein. Standardwert ist -1. Wert: Die ID des DotCode Structured Append Mode Barcodes.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Ermittelt die Anzahl der DotCode Structured Append Mode Barcodes. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. Wert: Die Anzahl des DotCode Structured Append Mode Barcodes.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. Standardwert ist false.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DotCodeExtendedParameters` zurück.

**Returns:** A string that represents this `DotCodeExtendedParameters`.

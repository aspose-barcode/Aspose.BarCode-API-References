---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert spezielle Daten des erkannten Aztec-Barcodes. Dieses Beispiel zeigt, wie man rohe Aztec‑Werte erhält let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /de/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Speichert spezielle Daten des erkannten Aztec-Barcodes. Dieses Beispiel zeigt, wie man rohe Aztec‑Werte erhält let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `AztecExtendedParameters`‑Wert entspricht. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Liefert die ID des Aztec‑Structured‑Append‑Mode‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Liefert die Anzahl der Barcodes im Aztec‑Structured‑Append‑Modus. Standardwert ist 0. Die Anzahl muss ein Wert zwischen 1 und 26 sein. Wert: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Liefert die Datei‑ID des Aztec‑Structured‑Append‑Modus. Standardwert ist ein leerer String. Wert: Die Datei‑ID des Aztec stru |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isReaderInitialization()](#isreaderinitialization) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `AztecExtendedParameters` zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `AztecExtendedParameters`‑Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Liefert die ID des Aztec‑Structured‑Append‑Mode‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist 0. Wert: Die Barcode‑ID des Aztec‑Structured‑Append‑Modus.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Liefert die Anzahl der Barcodes im Aztec‑Structured‑Append‑Modus. Standardwert ist 0. Die Anzahl muss ein Wert zwischen 1 und 26 sein. Wert: Die Barcode‑Anzahl des Aztec‑Structured‑Append‑Modus.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Liefert die Datei‑ID des Aztec‑Structured‑Append‑Modus. Standardwert ist ein leerer String. Wert: Die Datei‑ID des Aztec‑Structured‑Append‑Modus.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. Standardwert ist false.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `AztecExtendedParameters` zurück.

**Returns:** A string that represents this `AztecExtendedParameters`.

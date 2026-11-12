---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert spezielle Daten des erkannten DataMatrix‑Barcodes Dieses Beispiel zeigt, wie man rohe DataMatrix‑Werte erhält let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /de/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Speichert spezielle Daten des erkannten DataMatrix‑Barcodes Dieses Beispiel zeigt, wie man rohe DataMatrix‑Werte erhält let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen `DataMatrixExtendedParameters`‑Wert ist. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Liefert die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Anzahl der Barcodes sein. |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Liefert die Anzahl der DataMatrix‑Structured‑Append‑Modus‑Barcodes. Der Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein. |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Liefert die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Anzahl der Barcodes sein. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [isReaderProgramming()](#isreaderprogramming) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DataMatrixExtendedParameters` zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz gleich einem angegebenen `DataMatrixExtendedParameters`‑Wert ist.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Liefert die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1. Wert: Die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Liefert die Anzahl der DataMatrix‑Structured‑Append‑Modus‑Barcodes. Der Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein. Wert: Die Anzahl der DataMatrix‑Structured‑Append‑Modus‑Barcodes.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Liefert die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1. Wert: Die ID des DataMatrix‑Structured‑Append‑Modus‑Barcodes.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neu‑programmierung des Barcodelesers zu interpretieren. Standardwert ist false.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DataMatrixExtendedParameters` zurück.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.

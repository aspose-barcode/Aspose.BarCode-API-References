---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Speichert zusätzliche Informationen des erkannten DataBar-Barcodes."
type: docs
weight: 310
url: /de/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Speichert zusätzliche Informationen des erkannten DataBar-Barcodes.

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen DataBarExtendedParameters-Wert entspricht. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Liest das DataBar 2D Composite‑Komponenten‑Flag aus. Der Standardwert ist false. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses zurück. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen DataBarExtendedParameters-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | DataBarExtendedParameters-Wert zum Vergleich mit dieser Instanz. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Liest das DataBar 2D Composite‑Komponenten‑Flag aus. Der Standardwert ist false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses zurück.

**Returns:** A string that represents this .

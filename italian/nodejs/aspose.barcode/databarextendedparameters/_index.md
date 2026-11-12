---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza informazioni aggiuntive DataBar del barcode riconosciuto"
type: docs
weight: 310
url: /it/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Memorizza informazioni aggiuntive DataBar del barcode riconosciuto

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di DataBarExtendedParameters. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Ottiene il flag del componente composito DataBar 2D. Il valore predefinito è false. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di DataBarExtendedParameters.

| Parametro | Descrizione |
| --- | --- |
| obj | Valore DataBarExtendedParameters da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Ottiene il flag del componente composito DataBar 2D. Il valore predefinito è false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo.

**Returns:** A string that represents this .

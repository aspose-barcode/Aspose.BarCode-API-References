---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre"
type: docs
weight: 100
url: /it/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di BarCodeRegionParameters. |
| [getAngle()](#getangle) | Ottiene l'angolo del codice a barre (0-360). Valore: L'angolo per il codice a barre (0-360). |
| [getPoints()](#getpoints) | Ottiene l'array Points che delimita la regione del codice a barre Valore: Restituisce l'array Points che delimita la regione del codice a barre |
| [getQuadrangle()](#getquadrangle) | Ottiene il Quadrangle che delimita la regione del codice a barre Valore: Restituisce il Quadrangle che delimita la regione del codice a barre |
| [getRectangle()](#getrectangle) | Ottiene il Rectangle che delimita la regione del codice a barre Valore: Restituisce il Rectangle che delimita la regione del codice a barre |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeRegionParameters. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di BarCodeRegionParameters.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Ottiene l'angolo del codice a barre (0-360). Valore: L'angolo per il codice a barre (0-360).

### getPoints() {#getpoints}

Ottiene l'array Points che delimita la regione del codice a barre Valore: Restituisce l'array Points che delimita la regione del codice a barre

### getQuadrangle() {#getquadrangle}

Ottiene il Quadrangle che delimita la regione del codice a barre Valore: Restituisce il Quadrangle che delimita la regione del codice a barre

### getRectangle() {#getrectangle}

Ottiene il Rectangle che delimita la regione del codice a barre Valore: Restituisce il Rectangle che delimita la regione del codice a barre

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.

---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6."
type: docs
weight: 670
url: /es/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Clase para codificar y decodificar el texto de código MaxiCode para los modos 4, 5 y 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye codetext |
| [getHashCode()](#gethashcode) | Devuelve el código hash de esta instancia. |
| [getMessage()](#getmessage) | Obtiene el mensaje. |
| [getMode()](#getmode) | Obtiene el modo MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa la instancia a partir del codetext construido. |
| [setMessage()](#setmessage) | Establece el mensaje. |
| [setMode()](#setmode) | Establece el modo MaxiCode. El texto de código estándar solo se puede usar con los modos 4, 5 y 6. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor para comparar con esta instancia. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Construye codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Obtiene el mensaje.

### getMode() {#getmode}

Obtiene el modo MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Inicializa la instancia a partir del codetext construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setMessage() {#setmessage}

Establece el mensaje.

### setMode() {#setmode}

Establece el modo MaxiCode. El texto de código estándar solo se puede usar con los modos 4, 5 y 6.

---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de texto de código extendido para códigos QR 2D en modo ExtendedCodetext de QREncodeMode. Use la propiedad Display2DText de BarCodeBuilder para establecer el texto visible a rem"
type: docs
weight: 820
url: /es/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Generador de texto de código extendido para códigos QR 2D en modo ExtendedCodetext de QREncodeMode. Use la propiedad Display2DText de BarCodeBuilder para establecer el texto visible eliminando caracteres de gestión.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Agrega texto de código con el modo de compactación QR especificado a los elementos de texto de código extendido. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Agrega FNC1 en la primera posición a los elementos de texto de código extendido. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Agrega Separador de Grupo (GS - '\\u001D') a los elementos de texto de código extendido. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Agrega FNC1 en la segunda posición a los elementos de texto de código extendido. |
| [clear()](#clear) | Borra los elementos de codetext extendido |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de codetext extendido. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Agrega texto de código con el modo de compactación QR especificado a los elementos de texto de código extendido.

| Parámetro | Descripción |
| --- | --- |
| modo | Modo de compactación QR para el texto de código. |
| codetext | Texto de código en Unicode para agregar como un elemento de texto de código extendido. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Agrega FNC1 en la primera posición a los elementos de texto de código extendido.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Agrega Separador de Grupo (GS - '\\u001D') a los elementos de texto de código extendido.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Agrega FNC1 en la segunda posición a los elementos de texto de código extendido.

| Parámetro | Descripción |
| --- | --- |
| codetext | Valor del FNC1 en la segunda posición. |

### clear() {#clear}

Borra los elementos de codetext extendido

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de codetext extendido.

**Returns:** Extended codetext as string

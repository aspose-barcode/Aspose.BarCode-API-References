---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de Codetext."
type: docs
weight: 270
url: /es/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Parámetros de Codetext.

```js
new CodetextParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAlignment()](#getalignment) | Obtiene la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER. |
| [getColor()](#getcolor) | Especifique el color del CodeText mostrado. Valor predeterminado: BLACK. |
| [getFont()](#getfont) | Especifique la fuente del CodeText mostrado. Valor predeterminado: Arial 5pt regular. Se ignora si FontMode está configurado a FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. It i |
| [getLocation()](#getlocation) | Especifique la ubicación del CodeText mostrado, establezca CodeLocation.NONE para ocultar el CodeText. Valor predeterminado: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Especifique los ajustes de línea (saltos de línea) dentro del texto. Valor predeterminado: false. |
| [getSpace()](#getspace) | Espacio entre el CodeText y el BarCode en unidades. Valor predeterminado: 2pt. Se ignora para EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Establece la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER. |
| [setColor()](#setcolor) | Especifique el color del CodeText mostrado. Valor predeterminado: BLACK. |
| [setFont()](#setfont) | Especifique la fuente del CodeText mostrado. Valor predeterminado: Arial 5pt regular. Se ignora si FontMode está configurado a FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. It i |
| [setLocation()](#setlocation) | Especifique la ubicación del CodeText mostrado, establezca CodeLocation.NONE para ocultar el CodeText. Valor predeterminado: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Especifique los ajustes de línea (saltos de línea) dentro del texto. Valor predeterminado: false. |
| [setSpace()](#setspace) | Espacio entre el CodeText y el BarCode en unidades. Valor predeterminado: 2pt. Se ignora para EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este CodetextParameters. |

### getAlignment() {#getalignment}

Obtiene la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER.

### getColor() {#getcolor}

Especifique el color del CodeText mostrado. Valor predeterminado: BLACK.

### getFont() {#getfont}

Especifique la fuente del CodeText mostrado. Valor predeterminado: Arial 5pt regular. Se ignora si FontMode está configurado a FontMode.AUTO.

### getFontMode() {#getfontmode}

Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar FontMode.AUTO especialmente en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valor predeterminado: FontMode.AUTO.

### getLocation() {#getlocation}

Especifique la ubicación del CodeText mostrado, establezca CodeLocation.NONE para ocultar el CodeText. Valor predeterminado: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Especifique los ajustes de línea (saltos de línea) dentro del texto. Valor predeterminado: false.

### getSpace() {#getspace}

Espacio entre el CodeText y el BarCode en unidades. Valor predeterminado: 2pt. Se ignora para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Establece la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER.

### setColor() {#setcolor}

Especifique el color del CodeText mostrado. Valor predeterminado: BLACK.

### setFont() {#setfont}

Especifique la fuente del CodeText mostrado. Valor predeterminado: Arial 5pt regular. Se ignora si FontMode está configurado a FontMode.AUTO.

### setFontMode() {#setfontmode}

Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor de xDimension. Se recomienda usar FontMode.AUTO especialmente en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valor predeterminado: FontMode.AUTO.

### setLocation() {#setlocation}

Especifique la ubicación del CodeText mostrado, establezca CodeLocation.NONE para ocultar el CodeText. Valor predeterminado: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Especifique los ajustes de línea (saltos de línea) dentro del texto. Valor predeterminado: false.

### setSpace() {#setspace}

Espacio entre el CodeText y el BarCode en unidades. Valor predeterminado: 2pt. Se ignora para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este CodetextParameters.

**Returns:** A string that represents this CodetextParameters.

---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios."
type: docs
weight: 460
url: /es/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Clase para codificar y decodificar el texto incrustado en el código HIBC LIC que almacena datos primarios. Este ejemplo muestra cómo codificar y decodificar HIBC LIC usando HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [equals(obj)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICPrimaryDataCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construye codetext |
| [getData()](#getdata) | Identifica los datos primarios. |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [initFromString(constructedCodetext)](#initfromstring) | Inicializa la instancia a partir del codetext construido. |
| [setData()](#setdata) | Identifica los datos primarios. |

### equals(obj) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor especificado de `HIBCLICPrimaryDataCodetext`.

| Parámetro | Descripción |
| --- | --- |
| obj | Un valor `HIBCLICPrimaryDataCodetext` para comparar con esta instancia. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Construye codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Identifica los datos primarios.

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inicializa la instancia a partir del codetext construido.

| Parámetro | Descripción |
| --- | --- |
| constructedCodetext | Codetext construido. |

### setData() {#setdata}

Identifica los datos primarios.

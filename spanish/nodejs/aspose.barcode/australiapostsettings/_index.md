---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de decodificación de AustraliaPost."
type: docs
weight: 30
url: /es/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Parámetros de decodificación de AustraliaPost. Contiene parámetros que influyen en los datos reconocidos de la simbología AustraliaPost.

```js
new AustraliaPostSettings()
```

Constructor de AustraliaPostSettings

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Obtiene el Tipo de Interpretación para la Información del Cliente del código de barras AustralianPost. DEFAULT es CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el campo de Información del Cliente durante la decodificación |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Establece el Tipo de Interpretación para la Información del Cliente del código de barras AustralianPost. DEFAULT es CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el campo de Información del Cliente durante la decodificación |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Obtiene el Tipo de Interpretación para la Información del Cliente del código de barras AustralianPost. DEFAULT es CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

Establece el Tipo de Interpretación para la Información del Cliente del código de barras AustralianPost. DEFAULT es CustomerInformationInterpretingType.OTHER.

| Parámetro | Descripción |
| --- | --- |
| valor | El tipo de interpretación (CTable, NTable o Other) de la información del cliente para el código de barras AustralianPost |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

La bandera que obliga al decodificador AustraliaPost a ignorar los últimos patrones de relleno en el campo de Información del Cliente durante la decodificación como método CTable. El método de codificación CTable no tiene huecos en la tabla de codificación y la secuencia "333" de patrones de relleno se decodifica como la letra "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

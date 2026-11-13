---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "AustraliaPost avkodningsparametrar."
type: docs
weight: 30
url: /sv/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost avkodningsparametrar. Innehåller parametrar som påverkar den igenkända datan för AustraliaPost-symbologi.

```js
new AustraliaPostSettings()
```

AustraliaPostSettings-konstruktor

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Hämtar tolknings‑typen för kundinformation för AustralianPost‑streckkod. DEFAULT är CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Flaggan som tvingar AustraliaPost‑avkodaren att ignorera de sista fyllningsmönstren i kundinformationsfältet under avkodning. |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Ställer in tolknings‑typen för kundinformation för AustralianPost‑streckkod. DEFAULT är CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Flaggan som tvingar AustraliaPost‑avkodaren att ignorera de sista fyllningsmönstren i kundinformationsfältet under avkodning. |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Hämtar tolknings‑typen för kundinformation för AustralianPost‑streckkod. DEFAULT är CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Flaggan som tvingar AustraliaPost‑avkodaren att ignorera de sista fyllningsmönstren i kundinformationsfältet under avkodning som CTable‑metod. CTable‑kodningsmetoden har inga luckor i kodningstabellen och sekvensen "333" av fyllningsmönster avkodas som bokstaven "z".

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

Ställer in tolknings‑typen för kundinformation för AustralianPost‑streckkod. DEFAULT är CustomerInformationInterpretingType.OTHER.

| Parameter | Beskrivning |
| --- | --- |
| värde | Tolknings‑typen (CTable, NTable eller Other) för kundinformation för AustralianPost‑streckkod |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Flaggan som tvingar AustraliaPost‑avkodaren att ignorera de sista fyllningsmönstren i kundinformationsfältet under avkodning som CTable‑metod. CTable‑kodningsmetoden har inga luckor i kodningstabellen och sekvensen "333" av fyllningsmönster avkodas som bokstaven "z".

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

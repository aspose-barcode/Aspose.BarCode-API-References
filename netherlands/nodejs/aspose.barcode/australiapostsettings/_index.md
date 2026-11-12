---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "AustraliaPost-decodering parameters."
type: docs
weight: 30
url: /nl/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost-decodering parameters. Bevat parameters die invloed hebben op de herkende gegevens van de AustraliaPost-symbologie.

```js
new AustraliaPostSettings()
```

AustraliaPostSettings constructor

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Haalt het Interpreting Type op voor de Customer Information van AustralianPost BarCode. DEFAULT is CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | De vlag die de AustraliaPost-decoder dwingt om de laatste opvulpatronen in het Customer Information-veld te negeren tijdens het decoderen |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Stelt het Interpreting Type in voor de Customer Information van AustralianPost BarCode. DEFAULT is CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | De vlag die de AustraliaPost-decoder dwingt om de laatste opvulpatronen in het Customer Information-veld te negeren tijdens het decoderen |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Haalt het Interpreting Type op voor de Customer Information van AustralianPost BarCode. DEFAULT is CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

De vlag die de AustraliaPost-decoder dwingt om de laatste opvulpatronen in het Customer Information-veld te negeren tijdens het decoderen als CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderings tabel en de reeks \"333\" van opvulpatronen wordt gedecodeerd als de letter \"z\".

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

Stelt het Interpreting Type in voor de Customer Information van AustralianPost BarCode. DEFAULT is CustomerInformationInterpretingType.OTHER.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Het Interpreting Type (CTable, NTable of Other) van de Customer Information voor AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

De vlag die de AustraliaPost-decoder dwingt om de laatste opvulpatronen in het Customer Information-veld te negeren tijdens het decoderen als CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderings tabel en de reeks \"333\" van opvulpatronen wordt gedecodeerd als de letter \"z\".

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

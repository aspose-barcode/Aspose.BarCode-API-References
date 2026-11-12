---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "AustraliaPost-Dekodierungsparameter."
type: docs
weight: 30
url: /de/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

AustraliaPost-Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost-Symbologie haben.

```js
new AustraliaPostSettings()
```

AustraliaPostSettings-Konstruktor

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Gibt den Interpreting Type für die Customer Information des AustralianPost BarCode zurück. DEFAULT ist CustomerInformationInterpre. |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Das Flag, das den AustraliaPost-Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung zu ignorieren. |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Legt den Interpreting Type für die Customer Information des AustralianPost BarCode fest. DEFAULT ist CustomerInformationInterpre. |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Das Flag, das den AustraliaPost-Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung zu ignorieren. |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Gibt den Interpreting Type für die Customer Information des AustralianPost BarCode zurück. DEFAULT ist CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Das Flag, das den AustraliaPost-Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung als CTable-Methode zu ignorieren. Die CTable-Codierungsmethode hat keine Lücken in der Codierungstabelle und die Sequenz \"333\" von Füllmustern wird als Buchstabe \"z\" dekodiert.

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

Legt den Interpreting Type für die Customer Information des AustralianPost BarCode fest. DEFAULT ist CustomerInformationInterpretingType.OTHER.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Der Interpretationstyp (CTable, NTable oder Other) der Kundeninformation für den AustralianPost BarCode. |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Das Flag, das den AustraliaPost-Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung als CTable-Methode zu ignorieren. Die CTable-Codierungsmethode hat keine Lücken in der Codierungstabelle und die Sequenz \"333\" von Füllmustern wird als Buchstabe \"z\" dekodiert.

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

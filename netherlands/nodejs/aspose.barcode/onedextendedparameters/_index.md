---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Slaat speciale gegevens van een herkende 1D barcode op, zoals afzonderlijke codetekst en controlesom"
type: docs
weight: 720
url: /nl/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Slaat speciale gegevens van een herkende 1D barcode op, zoals afzonderlijke codetekst en controlesom

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven OneDExtendedParameters-waarde. |
| [getCheckSum()](#getchecksum) | Haalt de controlecode op voor 1D-barcodes. Waarde: De controlecode voor de 1D-barcode. |
| [getValue()](#getvalue) | Haalt de codetext op van 1D-barcodes zonder controlecode. Waarde: De codetext van 1D-barcodes zonder controlecode. |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [isEmpty()](#isempty) | Test of alle parameters alleen standaardwaarden hebben. Waarde: Retourneert `true ` als alle parameters alleen standaardwaarden hebben; o |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze OneDExtendedParameters. |

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven OneDExtendedParameters-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Haalt de controlecode op voor 1D-barcodes. Waarde: De controlecode voor de 1D-barcode.

### getValue() {#getvalue}

Haalt de codetext op van 1D-barcodes zonder controlecode. Waarde: De codetext van 1D-barcodes zonder controlecode.

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Test of alle parameters alleen standaardwaarden hebben. Waarde: Retourneert `true ` als alle parameters alleen standaardwaarden hebben; anders, `false `.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.

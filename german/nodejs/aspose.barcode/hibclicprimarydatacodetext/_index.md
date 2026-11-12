---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes, der Primärdaten speichert."
type: docs
weight: 460
url: /de/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Klasse zum Kodieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes, der Primärdaten speichert. Dieses Beispiel zeigt, wie man HIBC LIC mit HIBCLICPrimaryCodetext kodiert und dekodiert.

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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICPrimaryDataCodetext`-Wert entspricht. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [getData()](#getdata) | Identifiziert primäre Daten. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setData()](#setdata) | Identifiziert primäre Daten. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICPrimaryDataCodetext`-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein `HIBCLICPrimaryDataCodetext`-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Identifiziert primäre Daten.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setData() {#setdata}

Identifiziert primäre Daten.

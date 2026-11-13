---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för lagring av primära HIBC LIC‑data."
type: docs
weight: 800
url: /sv/nodejs/aspose.barcode/primarydata/
---

## PrimaryData class

Klass för lagring av primära HIBC LIC‑data.

```js
new PrimaryData()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `PrimaryData`-värde. |
| [getLabelerIdentificationCode()](#getlabeleridentificationcode) | Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, med |
| [getProductOrCatalogNumber()](#getproductorcatalognumber) | Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [getUnitOfMeasureID()](#getunitofmeasureid) | Identifierar enhetens måttenhet-ID. Enhetens måttenhet-ID måste vara ett heltal mellan 0 och 9. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [parseFromString(primaryDataCodetext)](#parsefromstring) | Instansierar primärdata från strängformat enligt HIBC LIC-specifikationen. |
| [setLabelerIdentificationCode()](#setlabeleridentificationcode) | Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, med |
| [setProductOrCatalogNumber()](#setproductorcatalognumber) | Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [setUnitOfMeasureID()](#setunitofmeasureid) | Identifierar enhetens måttenhet-ID. Enhetens måttenhet-ID måste vara ett heltal mellan 0 och 9. |
| [toString()](#tostring) | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `PrimaryData`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett `PrimaryData`-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getLabelerIdentificationCode() {#getlabeleridentificationcode}

Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, där det första tecknet alltid är alfabetiskt.

### getProductOrCatalogNumber() {#getproductorcatalognumber}

Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken.

### getUnitOfMeasureID() {#getunitofmeasureid}

Identifierar enhetens måttenhet-ID. Enhetens måttenhet-ID måste vara ett heltal mellan 0 och 9.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(primaryDataCodetext) {#parsefromstring}

Instansierar primärdata från strängformat enligt HIBC LIC-specifikationen.

| Parameter | Beskrivning |
| --- | --- |
| primaryDataCodetext | Formaterad sträng. |

### setLabelerIdentificationCode() {#setlabeleridentificationcode}

Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, där det första tecknet alltid är alfabetiskt.

### setProductOrCatalogNumber() {#setproductorcatalognumber}

Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken.

### setUnitOfMeasureID() {#setunitofmeasureid}

Identifierar enhetens måttenhet-ID. Enhetens måttenhet-ID måste vara ett heltal mellan 0 och 9.

### toString() {#tostring}

Konverterar data till strängformat enligt HIBC LIC-specifikationen.

**Returns:** Formatted string.

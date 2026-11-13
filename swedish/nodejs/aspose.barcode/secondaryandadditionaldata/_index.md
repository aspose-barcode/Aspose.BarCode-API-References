---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för lagring av sekundära och ytterligare HIBC LIC‑data."
type: docs
weight: 880
url: /sv/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Klass för lagring av sekundära och ytterligare HIBC LIC‑data.

```js
new SecondaryAndAdditionalData()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `SecondaryAndAdditionalData`-värde. |
| [getDateOfManufacture()](#getdateofmanufacture) | Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Defa |
| [getExpiryDate()](#getexpirydate) | Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None. |
| [getExpiryDateFormat()](#getexpirydateformat) | Identifierar format för utgångsdatum. |
| [getLotNumber()](#getlotnumber) | Identifierar parti- eller batchnummer. Parti/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken. . |
| [getQuantity()](#getquantity) | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Defa |
| [getSerialNumber()](#getserialnumber) | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng upp till 18 tecken lång. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | Instansierar sekundär och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen. |
| [setDateOfManufacture()](#setdateofmanufacture) | Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Defa |
| [setExpiryDate()](#setexpirydate) | Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None. |
| [setExpiryDateFormat()](#setexpirydateformat) | Identifierar format för utgångsdatum. |
| [setLotNumber()](#setlotnumber) | Identifierar parti- eller batchnummer. Parti/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken. . |
| [setQuantity()](#setquantity) | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Defa |
| [setSerialNumber()](#setserialnumber) | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng upp till 18 tecken lång. |
| [toString()](#tostring) | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `SecondaryAndAdditionalData`-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett `SecondaryAndAdditionalData`-värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None.

### getExpiryDateFormat() {#getexpirydateformat}

Identifierar format för utgångsdatum.

### getLotNumber() {#getlotnumber}

Identifierar parti- eller batchnummer. Parti/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken. .

### getQuantity() {#getquantity}

Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1

### getSerialNumber() {#getserialnumber}

Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng upp till 18 tecken lång.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

Instansierar sekundär och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen.

| Parameter | Beskrivning |
| --- | --- |
| secondaryDataCodetext | Formaterad sträng. |

### setDateOfManufacture() {#setdateofmanufacture}

Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None.

### setExpiryDateFormat() {#setexpirydateformat}

Identifierar format för utgångsdatum.

### setLotNumber() {#setlotnumber}

Identifierar parti- eller batchnummer. Parti/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken. .

### setQuantity() {#setquantity}

Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1

### setSerialNumber() {#setserialnumber}

Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng upp till 18 tecken lång.

### toString() {#tostring}

Konverterar data till strängformat enligt HIBC LIC-specifikationen.

**Returns:** Formatted string.

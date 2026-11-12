---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Extended codetext generator voor 2D QR barcodes voor ExtendedCodetext-modus van QREncodeMode. Gebruik de Display2DText-eigenschap van BarCodeBuilder om de zichtbare tekst in te stellen op rem"
type: docs
weight: 820
url: /nl/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Extended codetext generator voor 2D QR barcodes voor ExtendedCodetext-modus van QREncodeMode. Gebruik de Display2DText-eigenschap van BarCodeBuilder om de zichtbare tekst in te stellen op het verwijderen van beheer‑tekens.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Voegt codetext toe met de opgegeven QR-compressiemodus aan de uitgebreide codetext‑items. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Voegt FNC1 toe op de eerste positie aan de uitgebreide codetext‑items. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Voegt Group Separator (GS - '\\u001D') toe aan de uitgebreide codetext‑items. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Voegt FNC1 toe op de tweede positie aan de uitgebreide codetext‑items. |
| [clear()](#clear) | Wis de uitgebreide codetekstitems |
| [getExtendedCodetext()](#getextendedcodetext) | Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Voegt codetext toe met de opgegeven QR-compressiemodus aan de uitgebreide codetext‑items.

| Parameter | Beschrijving |
| --- | --- |
| modus | QR-compressiemodus voor de codetext. |
| codetext | Codetext in Unicode om toe te voegen als een uitgebreid codetext‑item. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Voegt FNC1 toe op de eerste positie aan de uitgebreide codetext‑items.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Voegt Group Separator (GS - '\\u001D') toe aan de uitgebreide codetext‑items.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Voegt FNC1 toe op de tweede positie aan de uitgebreide codetext‑items.

| Parameter | Beschrijving |
| --- | --- |
| codetext | Waarde van de FNC1 op de tweede positie |

### clear() {#clear}

Wis de uitgebreide codetekstitems

### getExtendedCodetext() {#getextendedcodetext}

Genereert uitgebreide codetekst vanuit de uitgebreide codetekst‑lijst.

**Returns:** Extended codetext as string

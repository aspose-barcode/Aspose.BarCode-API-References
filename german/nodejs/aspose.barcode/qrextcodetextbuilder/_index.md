---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext‑Generator für 2D‑QR‑Barcodes für den ExtendedCodetext‑Modus von QREncodeMode. Verwenden Sie die Eigenschaft Display2DText von BarCodeBuilder, um den sichtbaren Text zu entfernen."
type: docs
weight: 820
url: /de/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Erweiterter Codetext‑Generator für 2D‑QR‑Barcodes für den ExtendedCodetext‑Modus von QREncodeMode. Verwenden Sie die Eigenschaft Display2DText von BarCodeBuilder, um sichtbaren Text zu setzen, indem verwaltende Zeichen entfernt werden.

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

| Name | Beschreibung |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Fügt dem erweiterten Codetext‑Element den Codetext mit dem angegebenen QR‑Komprimierungsmodus hinzu. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Fügt dem erweiterten Codetext‑Element FNC1 an der ersten Position hinzu |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Fügt dem erweiterten Codetext‑Element den Gruppentrennzeichen (GS - '\\u001D') hinzu |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Fügt dem erweiterten Codetext‑Element FNC1 an der zweiten Position hinzu |
| [clear()](#clear) | Löscht erweiterte Codetext-Elemente |
| [getExtendedCodetext()](#getextendedcodetext) | Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Fügt dem erweiterten Codetext‑Element den Codetext mit dem angegebenen QR‑Komprimierungsmodus hinzu.

| Parameter | Beschreibung |
| --- | --- |
| Modus | QR‑Komprimierungsmodus für den Codetext. |
| codetext | Codetext in Unicode, der als erweitertes Codetext‑Element hinzugefügt werden soll. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Fügt dem erweiterten Codetext‑Element FNC1 an der ersten Position hinzu

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Fügt dem erweiterten Codetext‑Element den Gruppentrennzeichen (GS - '\\u001D') hinzu

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Fügt dem erweiterten Codetext‑Element FNC1 an der zweiten Position hinzu

| Parameter | Beschreibung |
| --- | --- |
| codetext | Wert von FNC1 an der zweiten Position |

### clear() {#clear}

Löscht erweiterte Codetext-Elemente

### getExtendedCodetext() {#getextendedcodetext}

Erzeugt erweiterten Codetext aus der erweiterten Codetext‑Liste.

**Returns:** Extended codetext as string

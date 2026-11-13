---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Kodtext‑parametrar."
type: docs
weight: 270
url: /sv/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Kodtext‑parametrar.

```js
new CodetextParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAlignment()](#getalignment) | Hämtar justeringen av kodtexten. Standardvärde: TextAlignment.CENTER. |
| [getColor()](#getcolor) | Ange färgen för den visade CodeText. Standardvärde: BLACK. |
| [getFont()](#getfont) | Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det i |
| [getLocation()](#getlocation) | Ange platsen för den visade CodeText, sätt till CodeLocation.NONE för att dölja CodeText. Standardvärde: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false. |
| [getSpace()](#getspace) | Avstånd mellan CodeText och streckkoden i enhetsvärde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Ställer in justeringen av kodtexten. Standardvärde: TextAlignment.CENTER. |
| [setColor()](#setcolor) | Ange färgen för den visade CodeText. Standardvärde: BLACK. |
| [setFont()](#setfont) | Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det i |
| [setLocation()](#setlocation) | Ange platsen för den visade CodeText, sätt till CodeLocation.NONE för att dölja CodeText. Standardvärde: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false. |
| [setSpace()](#setspace) | Avstånd mellan CodeText och streckkoden i enhetsvärde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av dessa CodetextParameters. |

### getAlignment() {#getalignment}

Hämtar justeringen av kodtexten. Standardvärde: TextAlignment.CENTER.

### getColor() {#getcolor}

Ange färgen för den visade CodeText. Standardvärde: BLACK.

### getFont() {#getfont}

Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO.

### getFontMode() {#getfontmode}

Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

### getLocation() {#getlocation}

Ange platsen för den visade CodeText, sätt till CodeLocation.NONE för att dölja CodeText. Standardvärde: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false.

### getSpace() {#getspace}

Avstånd mellan CodeText och streckkoden i enhetsvärde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Ställer in justeringen av kodtexten. Standardvärde: TextAlignment.CENTER.

### setColor() {#setcolor}

Ange färgen för den visade CodeText. Standardvärde: BLACK.

### setFont() {#setfont}

Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO.

### setFontMode() {#setfontmode}

Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

### setLocation() {#setlocation}

Ange platsen för den visade CodeText, sätt till CodeLocation.NONE för att dölja CodeText. Standardvärde: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false.

### setSpace() {#setspace}

Avstånd mellan CodeText och streckkoden i enhetsvärde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av dessa CodetextParameters.

**Returns:** A string that represents this CodetextParameters.

---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri Codetext."
type: docs
weight: 270
url: /it/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Parametri Codetext.

```js
new CodetextParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAlignment()](#getalignment) | Ottiene l'allineamento del testo del codice. Valore predefinito: TextAlignment.CENTER. |
| [getColor()](#getcolor) | Specifica il colore del CodeText visualizzato. Valore predefinito: BLACK. |
| [getFont()](#getfont) | Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore di xDimension. It i |
| [getLocation()](#getlocation) | Specifica la posizione del CodeText visualizzato, impostalo su CodeLocation.NONE per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Specifica l'andatura delle parole (interruzioni di riga) nel testo. Valore predefinito: false. |
| [getSpace()](#getspace) | Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Imposta l'allineamento del testo del codice. Valore predefinito: TextAlignment.CENTER. |
| [setColor()](#setcolor) | Specifica il colore del CodeText visualizzato. Valore predefinito: BLACK. |
| [setFont()](#setfont) | Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore di xDimension. It i |
| [setLocation()](#setlocation) | Specifica la posizione del CodeText visualizzato, impostalo su CodeLocation.NONE per nascondere il CodeText. Valore predefinito: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Specifica l'andatura delle parole (interruzioni di riga) nel testo. Valore predefinito: false. |
| [setSpace()](#setspace) | Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo CodetextParameters. |

### getAlignment() {#getalignment}

Ottiene l'allineamento del testo del codice. Valore predefinito: TextAlignment.CENTER.

### getColor() {#getcolor}

Specifica il colore del CodeText visualizzato. Valore predefinito: BLACK.

### getFont() {#getfont}

Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

### getFontMode() {#getfontmode}

Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore di xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

### getLocation() {#getlocation}

Specifica la posizione del CodeText visualizzato, impostalo su CodeLocation.NONE per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Specifica l'andatura delle parole (interruzioni di riga) nel testo. Valore predefinito: false.

### getSpace() {#getspace}

Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Imposta l'allineamento del testo del codice. Valore predefinito: TextAlignment.CENTER.

### setColor() {#setcolor}

Specifica il colore del CodeText visualizzato. Valore predefinito: BLACK.

### setFont() {#setfont}

Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

### setFontMode() {#setfontmode}

Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore di xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

### setLocation() {#setlocation}

Specifica la posizione del CodeText visualizzato, impostalo su CodeLocation.NONE per nascondere il CodeText. Valore predefinito: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Specifica l'andatura delle parole (interruzioni di riga) nel testo. Valore predefinito: false.

### setSpace() {#setspace}

Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo CodetextParameters.

**Returns:** A string that represents this CodetextParameters.

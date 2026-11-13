---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i den 4‑stegs Royal Mailmark-koden."
type: docs
weight: 580
url: /sv/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klass för kodning och avkodning av text som är inbäddad i den 4‑stegs Royal Mailmark-koden.

```js
new MailmarkCodetext()
```

Initierar en ny instans av klassen `MailmarkCodetext`.

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Hämtar streckkodstyp. |
| [getClass_()](#getclass-) | \"0\" - Null eller Test \"1\" - 1C (Detaljhandel) \"2\" - 2C (Detaljhandel) \"3\" - 3C (Detaljhandel) \"4\" - Premium (Detaljhandelspublicering Mail) (för pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Konstruera kodtext från Mailmark-data. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC och DP måste följa ett PAF-format. Nio tecken lång sträng som betecknar internationell \"XY11 \" (observera de 5 efterföljande s |
| [getFormat()](#getformat) | \"0\" – Null eller Test \"1\" – Bokstav \"2\" – Stor bokstav |
| [getItemID()](#getitemid) | Maximalt värde är 99999999. |
| [getSupplychainID()](#getsupplychainid) | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [getVersionID()](#getversionid) | För närvarande \"1\" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar Mailmark-data från konstruerad kodtext. |
| [setClass_()](#setclass-) | \"0\" - Null eller Test \"1\" - 1C (Detaljhandel) \"2\" - 2C (Detaljhandel) \"3\" - 3C (Detaljhandel) \"4\" - Premium (Detaljhandelspublicering Mail) (för pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC och DP måste följa ett PAF-format. Nio tecken lång sträng som betecknar internationell \"XY11 \" (observera de 5 efterföljande s |
| [setFormat()](#setformat) | \"0\" – Null eller Test \"1\" – LetterN \"2\" – Stor bokstav |
| [setItemID()](#setitemid) | Maximalt värde är 99999999. |
| [setSupplychainID()](#setsupplychainid) | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [setVersionID()](#setversionid) | För närvarande \"1\" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |

### getBarcodeType() {#getbarcodetype}

Hämtar streckkodstyp.

**Returns:** Barcode type.

### getClass_() {#getclass-}

\"0\" - Null eller Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (för potentiell framtida användning) \"5\" - Uppskjuten (Retail) \"6\" - Luft (Retail) (för potentiell framtida användning) \"7\" - Yta (Retail) (för potentiell framtida användning) \"8\" - Premium (Network Access) \"9\" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Konstruera kodtext från Mailmark-data.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC och DP måste följa ett PAF-format. Nio tecken lång sträng som betecknar internationell \"XY11 \" (observera de 5 efterföljande mellanslagen) eller ett mönster av tecken som betecknar en inhemsk sorteringskod. En inhemsk sorteringskod består av en utåtriktad postkod, en inåtriktad postkod och ett leveranspunktsuffix.

### getFormat() {#getformat}

\"0\" – Null eller Test \"1\" – Bokstav \"2\" – Stor bokstav

### getItemID() {#getitemid}

Maximalt värde är 99999999.

### getSupplychainID() {#getsupplychainid}

Maximala värden är 99 för Barcode C och 999999 för Barcode L.

### getVersionID() {#getversionid}

För närvarande \"1\" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning)

### initFromString(constructedCodetext) {#initfromstring}

Initierar Mailmark-data från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setClass_() {#setclass-}

\"0\" - Null eller Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (för potentiell framtida användning) \"5\" - Uppskjuten (Retail) \"6\" - Luft (Retail) (för potentiell framtida användning) \"7\" - Yta (Retail) (för potentiell framtida användning) \"8\" - Premium (Network Access) \"9\" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC och DP måste följa ett PAF-format. Nio tecken lång sträng som betecknar internationell \"XY11 \" (observera de 5 efterföljande mellanslagen) eller ett mönster av tecken som betecknar en inhemsk sorteringskod. En inhemsk sorteringskod består av en utåtriktad postkod, en inåtriktad postkod och ett leveranspunktsuffix.

### setFormat() {#setformat}

\"0\" – Null eller Test \"1\" – LetterN \"2\" – Stor bokstav

### setItemID() {#setitemid}

Maximalt värde är 99999999.

### setSupplychainID() {#setsupplychainid}

Maximala värden är 99 för Barcode C och 999999 för Barcode L.

### setVersionID() {#setversionid}

För närvarande \"1\" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning)

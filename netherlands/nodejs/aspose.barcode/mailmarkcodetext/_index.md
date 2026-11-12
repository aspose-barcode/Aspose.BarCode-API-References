---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4-state Royal Mailmark-code."
type: docs
weight: 580
url: /nl/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4-state Royal Mailmark-code.

```js
new MailmarkCodetext()
```

Initialiseert een nieuw exemplaar van de `MailmarkCodetext`-klasse.

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Haalt barcode type op. |
| [getClass_()](#getclass-) | "0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeer codetekst vanuit Mailmark-gegevens. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | De PC en DP moeten voldoen aan een PAF-formaat. Negen tekens lange string die internationale "XY11 " aangeeft (let op de 5 volgende s |
| [getFormat()](#getformat) | "0" – Null of Test "1" – Letter "2" – Grote Letter |
| [getItemID()](#getitemid) | Maximumwaarde is 99999999. |
| [getSupplychainID()](#getsupplychainid) | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [getVersionID()](#getversionid) | Momenteel "1" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |
| [setClass_()](#setclass-) | "0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | De PC en DP moeten voldoen aan een PAF-formaat. Negen tekens lange string die internationale "XY11 " aangeeft (let op de 5 volgende s |
| [setFormat()](#setformat) | "0" – Null of Test "1" – LetterN "2" – Grote Letter |
| [setItemID()](#setitemid) | Maximumwaarde is 99999999. |
| [setSupplychainID()](#setsupplychainid) | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [setVersionID()](#setversionid) | Momenteel "1" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |

### getBarcodeType() {#getbarcodetype}

Haalt barcode type op.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor potentieel toekomstig gebruik) "5" - Uitgesteld (Retail) "6" - Lucht (Retail) (voor potentieel toekomstig gebruik) "7" - Oppervlak (Retail) (voor potentieel toekomstig gebruik) "8" - Premium (Netwerktoegang) "9" - Standaard (Netwerktoegang)

### getConstructedCodetext() {#getconstructedcodetext}

Construeer codetekst vanuit Mailmark-gegevens.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

De PC en DP moeten voldoen aan een PAF-formaat. Een negen tekens lange string die internationale "XY11 " aangeeft (let op de 5 volgende spaties) of een patroon van tekens dat een binnenlandse sorteer­code aangeeft. Een binnenlandse sorteer­code bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix.

### getFormat() {#getformat}

"0" – Null of Test "1" – Letter "2" – Grote Letter

### getItemID() {#getitemid}

Maximumwaarde is 99999999.

### getSupplychainID() {#getsupplychainid}

Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L.

### getVersionID() {#getversionid}

Momenteel "1" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik)

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setClass_() {#setclass-}

"0" - Null of Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (voor potentieel toekomstig gebruik) "5" - Uitgesteld (Retail) "6" - Lucht (Retail) (voor potentieel toekomstig gebruik) "7" - Oppervlak (Retail) (voor potentieel toekomstig gebruik) "8" - Premium (Netwerktoegang) "9" - Standaard (Netwerktoegang)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

De PC en DP moeten voldoen aan een PAF-formaat. Een negen tekens lange string die internationale "XY11 " aangeeft (let op de 5 volgende spaties) of een patroon van tekens dat een binnenlandse sorteer­code aangeeft. Een binnenlandse sorteer­code bestaat uit een outward postcode, een inward postcode en een Delivery Point Suffix.

### setFormat() {#setformat}

"0" – Null of Test "1" – LetterN "2" – Grote Letter

### setItemID() {#setitemid}

Maximumwaarde is 99999999.

### setSupplychainID() {#setsupplychainid}

Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L.

### setVersionID() {#setversionid}

Momenteel "1" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik)

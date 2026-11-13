---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark-koden."
type: docs
weight: 570
url: /sv/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark-koden.

```js
new Mailmark2DCodetext()
```

Skapa standardinstans av Mailmark2DCodetext‑klassen.

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Hämtar streckkodstyp. |
| [getClass_()](#getclass-) | Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Konstruera kodtext från Mailmark-data. |
| [getCustomerContent()](#getcustomercontent) | Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Kodningsläge för Datamatrix‑streckkod. Standardvärde: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark‑typ definierar storleken på Data Matrix‑streckkoden. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken |
| [getInformationTypeID()](#getinformationtypeid) | Identifierar Royal Mail Mailmark‑streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad |
| [getItemID()](#getitemid) | Identifierar det unika objektet inom Supply Chain‑ID. Varje Mailmark‑streckkod måste bära ett ID så att den kan vara un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Innehåller Return to Sender‑postkod men ingen DPS. PC:n (utan DPS) måste följa ett PAF®‑format. |
| [getRTSFlag()](#getrtsflag) | Flagga som indikerar vilken nivå av Return to Sender‑tjänst som begärs. |
| [getSupplyChainID()](#getsupplychainid) | Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identifierar UPU‑lands‑ID. Maxlängd: 4 tecken. |
| [getVersionID()](#getversionid) | Identifierar streckkodsversionen som är relevant för varje Information Type‑ID. Giltiga värden: För närvarande '1'. '0' & '2' till '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar Mailmark-data från konstruerad kodtext. |
| [setClass_(value)](#setclass-) | Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Kodningsläge för Datamatrix‑streckkod. Standardvärde: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark‑typ definierar storleken på Data Matrix‑streckkoden. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken |
| [setInformationTypeID(value)](#setinformationtypeid) | Identifierar Royal Mail Mailmark‑streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad |
| [setItemID(value)](#setitemid) | Identifierar det unika objektet inom Supply Chain‑ID. Varje Mailmark‑streckkod måste bära ett ID så att den kan vara un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Innehåller Return to Sender‑postkod men ingen DPS. PC:n (utan DPS) måste följa ett PAF®‑format. |
| [setRTSFlag()](#setrtsflag) | Flagga som indikerar vilken nivå av Return to Sender‑tjänst som begärs. |
| [setSupplyChainID(value)](#setsupplychainid) | Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identifierar UPU‑lands‑ID. Maxlängd: 4 tecken. |
| [setVersionID(value)](#setversionid) | Identifierar streckkodsversionen som är relevant för varje Information Type‑ID. Giltiga värden: För närvarande '1'. '0' & '2' till '9' an |

### getBarcodeType() {#getbarcodetype}

Hämtar streckkodstyp.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Deffered (Detaljhandel) '8' - Premium (Nätverksåtkomst) '9' - Standard (Nätverksåtkomst)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Konstruera kodtext från Mailmark-data.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Kodningsläge för Datamatrix‑streckkod. Standardvärde: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark‑typ definierar storleken på Data Matrix‑streckkoden.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken. Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®‑format.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identifierar Royal Mail Mailmark‑streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad 'A' - Online‑postage 'B' - Franking 'C' - Konsolidering

**Returns:** Information type ID

### getItemID() {#getitemid}

Identifierar det unika objektet inom Supply Chain‑ID. Varje Mailmark‑streckkod måste bära ett ID så att den kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Innehåller Return to Sender‑postkod men ingen DPS. PC:n (utan DPS) måste följa ett PAF®‑format.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Flagga som indikerar vilken nivå av Return to Sender‑tjänst som begärs.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identifierar UPU‑lands‑ID. Maxlängd: 4 tecken.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identifierar streckkodsversionen som är relevant för varje Information Type‑ID. Giltiga värden: För närvarande '1'. '0' & '2' till '9' och 'A' till 'Z' reserverade för potentiell framtida användning.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Initierar Mailmark-data från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setClass_(value) {#setclass-}

Identifierar objektets klass. Giltiga värden: '1' - 1C (Detaljhandel) '2' - 2C (Detaljhandel) '3' - Ekonomi (Detaljhandel) '5' - Deffered (Detaljhandel) '8' - Premium (Nätverksåtkomst) '9' - Standard (Nätverksåtkomst)

| Parameter | Beskrivning |
| --- | --- |
| värde | klass för objektet |

### setCustomerContent(value) {#setcustomercontent}

Valfritt utrymme för kundens bruk. Maxlängd per typ: Typ 7: 6 tecken Typ 9: 45 tecken Typ 29: 25 tecken

| Parameter | Beskrivning |
| --- | --- |
| värde | Kundinnehåll |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Kodningsläge för Datamatrix‑streckkod. Standardvärde: DataMatrixEncodeMode.C40.

| Parameter | Beskrivning |
| --- | --- |
| värde | Kodningsläge för Datamatrix-streckkod. |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark‑typ definierar storleken på Data Matrix‑streckkoden.

| Parameter | Beskrivning |
| --- | --- |
| värde | Storlek på Data Matrix-streckkod |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Innehåller postnumret för leveransadressen med DPS. Om inlandet innehåller postnumret/DP följande antal tecken. Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®‑format.

| Parameter | Beskrivning |
| --- | --- |
| värde | postnumret för leveransadressen med DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identifierar Royal Mail Mailmark‑streckkodens nyttolast för varje produkttyp. Giltiga värden: '0' - Inrikes sorterad & osorterad 'A' - Online‑postage 'B' - Franking 'C' - Konsolidering

| Parameter | Beskrivning |
| --- | --- |
| värde | Informationstyp-ID |

### setItemID(value) {#setitemid}

Identifierar det unika objektet inom Supply Chain‑ID. Varje Mailmark‑streckkod måste bära ett ID så att den kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999.

| Parameter | Beskrivning |
| --- | --- |
| värde | objekt inom leveranskedjans ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Innehåller Return to Sender‑postkod men ingen DPS. PC:n (utan DPS) måste följa ett PAF®‑format.

| Parameter | Beskrivning |
| --- | --- |
| värde | Retur till avsändarens postnummer men utan DPS |

### setRTSFlag() {#setrtsflag}

Flagga som indikerar vilken nivå av Return to Sender‑tjänst som begärs.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999.

| Parameter | Beskrivning |
| --- | --- |
| värde | Leveranskedje-ID |

### setUPUCountryID(value) {#setupucountryid}

Identifierar UPU‑lands‑ID. Maxlängd: 4 tecken.

| Parameter | Beskrivning |
| --- | --- |
| värde | Land-ID |

### setVersionID(value) {#setversionid}

Identifierar streckkodsversionen som är relevant för varje Information Type‑ID. Giltiga värden: För närvarande '1'. '0' & '2' till '9' och 'A' till 'Z' reserverade för potentiell framtida användning.

| Parameter | Beskrivning |
| --- | --- |
| värde | Versions-ID |

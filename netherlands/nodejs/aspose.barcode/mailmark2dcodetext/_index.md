---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code."
type: docs
weight: 570
url: /nl/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code.

```js
new Mailmark2DCodetext()
```

Maak een standaardinstantie van de Mailmark2DCodetext‑klasse.

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Haalt barcode type op. |
| [getClass_()](#getclass-) | Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeer codetekst vanuit Mailmark-gegevens. |
| [getCustomerContent()](#getcustomercontent) | Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Encodeermodus van Datamatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens |
| [getInformationTypeID()](#getinformationtypeid) | Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. Geldige waarden: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark barcode moet een ID dragen zodat het kan worden un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Bevat de Retour naar Afzender postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| [getRTSFlag()](#getrtsflag) | Vlag die aangeeft welk niveau van Retour naar Afzender service wordt aangevraagd. |
| [getSupplyChainID()](#getsupplychainid) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identificeert de UPU land-ID. Maximale lengte: 4 tekens. |
| [getVersionID()](#getversionid) | Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: Momenteel '1'. '0' & '2' tot '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |
| [setClass_(value)](#setclass-) | Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Encodeermodus van Datamatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens |
| [setInformationTypeID(value)](#setinformationtypeid) | Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. Geldige waarden: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark barcode moet een ID dragen zodat het kan worden un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Bevat de Retour naar Afzender postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| [setRTSFlag()](#setrtsflag) | Vlag die aangeeft welk niveau van Retour naar Afzender service wordt aangevraagd. |
| [setSupplyChainID(value)](#setsupplychainid) | Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identificeert de UPU land-ID. Maximale lengte: 4 tekens. |
| [setVersionID(value)](#setversionid) | Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: Momenteel '1'. '0' & '2' tot '9' an |

### getBarcodeType() {#getbarcodetype}

Haalt barcode type op.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Construeer codetekst vanuit Mailmark-gegevens.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Encodeermodus van Datamatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark-type definieert de grootte van de Data Matrix-barcode.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens. Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identificeert de Royal Mail Mailmark barcode payload voor elk producttype. Geldige waarden: '0' - Binnenlands gesorteerd & onsorteerd 'A' - Online postzegel 'B' - Frankering 'C' - Consolidatie

**Returns:** Information type ID

### getItemID() {#getitemid}

Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark barcode moet een ID dragen zodat het gedurende ten minste 90 dagen uniek kan worden geïdentificeerd. Maximale waarde: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Bevat de Retour naar Afzender postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Vlag die aangeeft welk niveau van Retour naar Afzender service wordt aangevraagd.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identificeert de UPU land-ID. Maximale lengte: 4 tekens.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: Momenteel '1'. '0' & '2' tot '9' en 'A' tot 'Z' gereserveerd voor mogelijk toekomstig gebruik.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setClass_(value) {#setclass-}

Identificeert de klasse van het item. Geldige waarden: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

| Parameter | Beschrijving |
| --- | --- |
| waarde | klasse van het item |

### setCustomerContent(value) {#setcustomercontent}

Optionele ruimte voor gebruik door de klant. Maximale lengte per type: Type 7: 6 tekens Type 9: 45 tekens Type 29: 25 tekens

| Parameter | Beschrijving |
| --- | --- |
| waarde | Klantinhoud |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Encodeermodus van Datamatrix-barcode. Standaardwaarde: DataMatrixEncodeMode.C40.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Encodeermodus van Datamatrix barcode. |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark-type definieert de grootte van de Data Matrix-barcode.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Grootte van Data Matrix barcode |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Bevat de postcode van het afleveradres met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens. Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat.

| Parameter | Beschrijving |
| --- | --- |
| waarde | de postcode van het afleveradres met DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identificeert de Royal Mail Mailmark barcode payload voor elk producttype. Geldige waarden: '0' - Binnenlands gesorteerd & onsorteerd 'A' - Online postzegel 'B' - Frankering 'C' - Consolidatie

| Parameter | Beschrijving |
| --- | --- |
| waarde | Informatietype-ID |

### setItemID(value) {#setitemid}

Identificeert het unieke item binnen de Supply Chain ID. Elke Mailmark barcode moet een ID dragen zodat het gedurende ten minste 90 dagen uniek kan worden geïdentificeerd. Maximale waarde: 99999999.

| Parameter | Beschrijving |
| --- | --- |
| waarde | item binnen de Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Bevat de Retour naar Afzender postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Retour naar Afzender postcode maar geen DPS |

### setRTSFlag() {#setrtsflag}

Vlag die aangeeft welk niveau van Retour naar Afzender service wordt aangevraagd.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identificeert de unieke groep klanten die bij de verzending betrokken zijn. Maximale waarde: 9999999.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Supply chain-ID |

### setUPUCountryID(value) {#setupucountryid}

Identificeert de UPU land-ID. Maximale lengte: 4 tekens.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Land-ID |

### setVersionID(value) {#setversionid}

Identificeert de barcodeversie die relevant is voor elke Information Type ID. Geldige waarden: Momenteel '1'. '0' & '2' tot '9' en 'A' tot 'Z' gereserveerd voor mogelijk toekomstig gebruik.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Versie-ID |

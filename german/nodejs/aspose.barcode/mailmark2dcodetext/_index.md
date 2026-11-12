---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den Royal Mail 2D Mailmark‑Code eingebetteten Textes."
type: docs
weight: 570
url: /de/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Klasse zum Kodieren und Dekodieren des in den Royal Mail 2D Mailmark‑Code eingebetteten Textes.

```js
new Mailmark2DCodetext()
```

Erstellt eine Standardinstanz der Mailmark2DCodetext‑Klasse.

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ermittelt den Barcode-Typ. |
| [getClass_()](#getclass-) | Identifiziert die Klasse des Elements. Gültige Werte: '1' - 1C (Einzelhandel) '2' - 2C (Einzelhandel) '3' - Economy (Einzelhandel) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext aus Mailmark-Daten. |
| [getCustomerContent()](#getcustomercontent) | Optionaler Raum zur Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen. |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Kodierungsmodus des Datamatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Inland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen |
| [getInformationTypeID()](#getinformationtypeid) | Identifiziert die Royal‑Mail‑Mailmark‑Barcode‑Nutzlast für jeden Produkttyp. Gültige Werte: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | Identifiziert das eindeutige Element innerhalb der Supply Chain ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er eindeutig identifiziert werden kann. |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Enthält den Rücksendungs-Postcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen. |
| [getRTSFlag()](#getrtsflag) | Kennzeichen, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird. |
| [getSupplyChainID()](#getsupplychainid) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [getVersionID()](#getversionid) | Identifiziert die Barcode‑Version in Bezug auf jede Informations‑Typ‑ID. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |
| [setClass_(value)](#setclass-) | Identifiziert die Klasse des Elements. Gültige Werte: '1' - 1C (Einzelhandel) '2' - 2C (Einzelhandel) '3' - Economy (Einzelhandel) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Optionaler Raum zur Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen Typ 9: 45 Zeichen Typ 29: 25 Zeichen. |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Kodierungsmodus des Datamatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Inland enthält die Postleitzahl/DP die folgende Anzahl von Zeichen |
| [setInformationTypeID(value)](#setinformationtypeid) | Identifiziert die Royal‑Mail‑Mailmark‑Barcode‑Nutzlast für jeden Produkttyp. Gültige Werte: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | Identifiziert das eindeutige Element innerhalb der Supply Chain ID. Jeder Mailmark-Barcode muss eine ID tragen, damit er eindeutig identifiziert werden kann. |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Enthält den Rücksendungs-Postcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen. |
| [setRTSFlag()](#setrtsflag) | Kennzeichen, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird. |
| [setSupplyChainID(value)](#setsupplychainid) | Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen. |
| [setVersionID(value)](#setversionid) | Identifiziert die Barcode‑Version in Bezug auf jede Informations‑Typ‑ID. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und |

### getBarcodeType() {#getbarcodetype}

Ermittelt den Barcode-Typ.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identifiziert die Klasse des Elements. Gültige Werte: '1' – 1C (Einzelhandel) '2' – 2C (Einzelhandel) '3' – Economy (Einzelhandel) '5' – Deffered (Einzelhandel) '8' – Premium (Netzwerkzugriff) '9' – Standard (Netzwerkzugriff)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext aus Mailmark-Daten.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Optionaler Raum für die Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen, Typ 9: 45 Zeichen, Typ 29: 25 Zeichen.

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Kodierungsmodus des Datamatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Inland enthält die Postleitzahl/DP die folgende Zeichenanzahl: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und das DPS müssen einem gültigen PAF®‑Format entsprechen.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identifiziert die Royal Mail Mailmark‑Barcode‑Nutzlast für jeden Produkttyp. Gültige Werte: '0' – Inland sortiert & unsortiert, 'A' – Online‑Porto, 'B' – Frankierung, 'C' – Konsolidierung.

**Returns:** Information type ID

### getItemID() {#getitemid}

Identifiziert das eindeutige Element innerhalb der Supply Chain ID. Jeder Mailmark‑Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Enthält den Rücksendungs-Postcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Kennzeichen, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identifiziert die Barcode‑Version in Bezug auf jede Informations‑Typ‑ID. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und 'A' bis 'Z' sind reserviert für mögliche zukünftige Nutzung.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert Mailmark-Daten aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setClass_(value) {#setclass-}

Identifiziert die Klasse des Elements. Gültige Werte: '1' – 1C (Einzelhandel) '2' – 2C (Einzelhandel) '3' – Economy (Einzelhandel) '5' – Deffered (Einzelhandel) '8' – Premium (Netzwerkzugriff) '9' – Standard (Netzwerkzugriff)

| Parameter | Beschreibung |
| --- | --- |
| Wert | Klasse des Elements |

### setCustomerContent(value) {#setcustomercontent}

Optionaler Raum für die Nutzung durch den Kunden. Maximale Länge je Typ: Typ 7: 6 Zeichen, Typ 9: 45 Zeichen, Typ 29: 25 Zeichen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Kundeninhalt |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Kodierungsmodus des Datamatrix‑Barcodes. Standardwert: DataMatrixEncodeMode.C40.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Kodierungsmodus des Datamatrix‑Barcodes. |

### setDataMatrixType(value) {#setdatamatrixtype}

Der 2D‑Mailmark‑Typ definiert die Größe des Data‑Matrix‑Barcodes.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Größe des Data‑Matrix‑Barcodes |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Enthält die Postleitzahl der Lieferadresse mit DPS. Bei Inland enthält die Postleitzahl/DP die folgende Zeichenanzahl: Gebiet (1 oder 2 Zeichen) Bezirk (1 oder 2 Zeichen) Sektor (1 Zeichen) Einheit (2 Zeichen) DPS (2 Zeichen). Die Postleitzahl und das DPS müssen einem gültigen PAF®‑Format entsprechen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | die Postleitzahl der Lieferadresse mit DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identifiziert die Royal Mail Mailmark‑Barcode‑Nutzlast für jeden Produkttyp. Gültige Werte: '0' – Inland sortiert & unsortiert, 'A' – Online‑Porto, 'B' – Frankierung, 'C' – Konsolidierung.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Informations‑Typ‑ID |

### setItemID(value) {#setitemid}

Identifiziert das eindeutige Element innerhalb der Supply Chain ID. Jeder Mailmark‑Barcode muss eine ID tragen, damit er mindestens 90 Tage eindeutig identifiziert werden kann. Maximalwert: 99999999.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Element innerhalb der Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Enthält den Rücksendungs-Postcode, jedoch kein DPS. Der PC (ohne DPS) muss dem PAF®‑Format entsprechen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Rücksendungs‑Postcode, jedoch kein DPS |

### setRTSFlag() {#setrtsflag}

Kennzeichen, das angibt, welche Ebene des Rücksende‑Dienstes angefordert wird.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identifiziert die eindeutige Kundengruppe, die am Versand beteiligt ist. Maximalwert: 9999999.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Supply‑Chain‑ID |

### setUPUCountryID(value) {#setupucountryid}

Identifiziert die UPU-Ländercode-ID. Maximale Länge: 4 Zeichen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Länder‑ID |

### setVersionID(value) {#setversionid}

Identifiziert die Barcode‑Version in Bezug auf jede Informations‑Typ‑ID. Gültige Werte: Derzeit '1'. '0' & '2' bis '9' und 'A' bis 'Z' sind reserviert für mögliche zukünftige Nutzung.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Versions‑ID |

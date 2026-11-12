---
title: "Adresse"
linktitle: "Adresse"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Adresse des Gläubigers oder Schuldners."
type: docs
weight: 10
url: /de/nodejs/aspose.barcode/address/
---

## Address class

Adresse des Gläubigers oder Schuldners. Sie können entweder Straße, Hausnummer, Postleitzahl und Ort (type structured address) oder Adresszeile 1 und 2 (type combined address elements) festlegen. Der Typ wird automatisch gesetzt, sobald eines dieser Felder gesetzt ist. Vor dem Setzen der Felder ist der address type unbestimmt. Wenn Felder beider Typen gesetzt werden, wird der address type konfliktär. Name und Ländercode müssen immer gesetzt sein, es sei denn, alle Felder sind leer.

```js
new Address()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [clear()](#clear) | Löscht alle Felder und setzt den Typ auf AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [getAddressLine1()](#getaddressline1) | Liest die Adresszeile 1. Die Adresszeile 1 enthält den Straßennamen, die Hausnummer oder das Postfach. Das Setzen dieses Feldes setzt die addr |
| [getAddressLine2()](#getaddressline2) | Liest die Adresszeile 2. Die Adresszeile 2 enthält Postleitzahl und Ort. Das Setzen dieses Feldes setzt den address type auf Addre |
| [getCountryCode()](#getcountrycode) | Liest den zweibuchstabigen ISO-Ländercode. Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null oder leere val |
| [getHouseNo()](#gethouseno) | Liest die Hausnummer. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressTyp ist |
| [getName()](#getname) | Liest den Namen, entweder Vor- und Nachname einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [getPostalCode()](#getpostalcode) | Liest die Postleitzahl. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressType ist. |
| [getStreet()](#getstreet) | Liest die Straße. Die Straße muss ohne Hausnummer angegeben werden. Das Setzen dieses Feldes setzt den address type auf AddressT |
| [getTown()](#gettown) | Liest die Stadt oder den Ort. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressTyp ist. |
| [getType()](#gettype) | Liest den address type. Der address type wird automatisch gesetzt, indem entweder Straße / Hausnummer oder Adresszeile 1 a |
| [hashCode()](#hashcode) | Liest den Hashcode für diese Instanz. |
| [setAddressLine1(value:)](#setaddressline1) | Setzt die Adresszeile 1. Die Adresszeile 1 enthält den Straßennamen, die Hausnummer oder das Postfach. Das Setzen dieses Feldes setzt die addr |
| [setAddressLine2(value:)](#setaddressline2) | Setzt die Adresszeile 2. Die Adresszeile 2 enthält Postleitzahl und Ort. Das Setzen dieses Feldes setzt den address type auf Addre |
| [setCountryCode(value)](#setcountrycode) | Setzt den zweibuchstabigen ISO-Ländercode. Der Ländercode ist obligatorisch, es sei denn, die gesamte Adresse enthält null oder leere val |
| [setHouseNo(value:)](#sethouseno) | Setzt die Hausnummer. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressTyp ist. |
| [setName(value:)](#setname) | Setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [setPostalCode(value)](#setpostalcode) | Setzt die Postleitzahl. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressType ist. |
| [setStreet(value:)](#setstreet) | Setzt die Straße. Die Straße muss ohne Hausnummer angegeben werden. Das Setzen dieses Feldes setzt den address type auf AddressT |
| [setTown(value)](#settown) | Setzt die Stadt oder den Ort. Das Setzen dieses Feldes setzt den address type auf AddressType.STRUCTURED, sofern er nicht bereits AddressTyp ist. |

### clear() {#clear}

Löscht alle Felder und setzt den Typ auf AddressType.UNDETERMINED.

### equals(obj) {#equals}

Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

| Parameter | Beschreibung |
| --- | --- |
| obj | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Liest die Adresszeile 1. Die Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.COMBINED_ELEMENTS, sofern er nicht bereits AddressType.STRUCTURED ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Liest die Adresszeile 2. Die Adresszeile 2 enthält Postleitzahl und Ort. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.COMBINED_ELEMENTS, sofern er nicht bereits AddressType.STRUCTURED ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es verpflichtend.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Liest den zweibuchstabigen ISO-Ländercode. Der Ländercode ist verpflichtend, sofern die gesamte Adresse nicht null oder leere Werte enthält.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Liest die Hausnummer. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

**Returns:** The house number.

### getName() {#getname}

Liest den Namen, entweder Vor- und Nachname einer natürlichen Person oder den Firmennamen einer juristischen Person.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Liest die Postleitzahl. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es verpflichtend.

**Returns:** The postal code.

### getStreet() {#getstreet}

Liest die Straße. Die Straße muss ohne Hausnummer angegeben werden. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

**Returns:** The street.

### getTown() {#gettown}

Liest die Stadt oder Gemeinde. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es verpflichtend.

**Returns:** The town or city.

### getType() {#gettype}

Liest den Adresstyp. Der Adresstyp wird automatisch gesetzt, indem entweder Straße / Hausnummer oder Adresszeile 1 und 2 gesetzt werden. Vor dem Setzen der Felder ist der Adresstyp Undetermined. Wenn Felder beider Typen gesetzt werden, wird der Adresstyp zu Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Liest den Hashcode für diese Instanz.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Setzt die Adresszeile 1. Die Adresszeile 1 enthält Straßenname, Hausnummer oder Postfach. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.COMBINED_ELEMENTS, sofern er nicht bereits AddressType.STRUCTURED ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet und ist optional.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Adresszeile 1. |

### setAddressLine2(value:) {#setaddressline2}

Setzt die Adresszeile 2. Die Adresszeile 2 enthält Postleitzahl und Ort. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.COMBINED_ELEMENTS, sofern er nicht bereits AddressType.STRUCTURED ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für kombinierte Elemente-Adressen verwendet. Für diesen Typ ist es verpflichtend.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Adresszeile 2. |

### setCountryCode(value) {#setcountrycode}

Setzt den zweibuchstabigen ISO-Ländercode. Der Ländercode ist verpflichtend, sofern die gesamte Adresse nicht null oder leere Werte enthält.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Der ISO-Ländercode. |

### setHouseNo(value:) {#sethouseno}

Legt die Hausnummer fest. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Hausnummer. |

### setName(value:) {#setname}

Setzt den Namen, entweder Vor- und Nachname einer natürlichen Person oder den Firmennamen einer juristischen Person.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Der Name. |

### setPostalCode(value) {#setpostalcode}

Legt die Postleitzahl fest. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Die Postleitzahl. |

### setStreet(value:) {#setstreet}

Legt die Straße fest. Die Straße muss ohne Hausnummer angegeben werden. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Straße. |

### setTown(value) {#settown}

Legt die Stadt oder Gemeinde fest. Das Setzen dieses Feldes setzt den Adresstyp auf AddressType.STRUCTURED, sofern er nicht bereits AddressType.COMBINED_ELEMENTS ist; in diesem Fall wird er zu AddressType.CONFLICTING. Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Die Stadt oder Gemeinde. |

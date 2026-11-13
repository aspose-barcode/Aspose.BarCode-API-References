---
title: "Adress"
linktitle: "Adress"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Adress för borgenär eller gäldenär."
type: docs
weight: 10
url: /sv/nodejs/aspose.barcode/address/
---

## Address class

Adress för borgenär eller gäldenär. Du kan antingen ange gata, husnummer, postnummer och ort (typ strukturerad adress) eller adressrad 1 och 2 (typ kombinerade adresselement). Typen sätts automatiskt så snart någon av dessa fält är ifyllda. Innan fälten sätts är adress‑typen obestämd. Om fält av båda typerna anges blir adress‑typen konfliktfylld. Namn och landskod måste alltid anges om inte alla fält är tomma.

```js
new Address()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [clear()](#clear) | Rensar alla fält och sätter typen till AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [getAddressLine1()](#getaddressline1) | Hämtar adressrad 1. Adressrad 1 innehåller gatunamn, husnummer eller postbox. Att ställa in detta fält sätter adressen |
| [getAddressLine2()](#getaddressline2) | Hämtar adressrad 2. Adressrad 2 innehåller postnummer och ort. Att ställa in detta fält sätter adressens typ till Addre |
| [getCountryCode()](#getcountrycode) | Hämtar den tvåbokstaviga ISO-landkoden. Landkoden är obligatorisk om inte hela adressen innehåller null eller tomma värden |
| [getHouseNo()](#gethouseno) | Hämtar husnumret. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressTyp |
| [getName()](#getname) | Hämtar namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person. |
| [getPostalCode()](#getpostalcode) | Hämtar postnumret. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType. |
| [getStreet()](#getstreet) | Hämtar gatan. Gatan måste anges utan husnummer. Att ställa in detta fält sätter adresstypen till AddressT |
| [getTown()](#gettown) | Hämtar orten eller staden. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressTyp |
| [getType()](#gettype) | Hämtar adress typen. Adresstypen sätts automatiskt genom att antingen ange gata / husnummer eller adressrad 1 a |
| [hashCode()](#hashcode) | Hämtar hash‑koden för detta objekt. |
| [setAddressLine1(value:)](#setaddressline1) | Ställer in adressrad 1. Adressrad 1 innehåller gatunamn, husnummer eller postbox. Att ställa in detta fält sätter adressen |
| [setAddressLine2(value:)](#setaddressline2) | Ställer in adressrad 2. Adressrad 2 innehåller postnummer och ort. Att ställa in detta fält sätter adressens typ till Addre |
| [setCountryCode(value)](#setcountrycode) | Ställer in den tvåbokstaviga ISO-landkoden. Landkoden är obligatorisk om inte hela adressen innehåller null eller tomma värden |
| [setHouseNo(value:)](#sethouseno) | Ställer in husnumret. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressTyp |
| [setName(value:)](#setname) | Ställer in namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person. |
| [setPostalCode(value)](#setpostalcode) | Ställer in postnumret. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType |
| [setStreet(value:)](#setstreet) | Ställer in gatan. Gatan måste anges utan husnummer. Att ställa in detta fält sätter adresstypen till AddressT |
| [setTown(value)](#settown) | Ställer in orten eller staden. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressTyp |

### clear() {#clear}

Rensar alla fält och sätter typen till AddressType.UNDETERMINED.

### equals(obj) {#equals}

Bestämmer om det angivna objektet är lika med det aktuella objektet.

| Parameter | Beskrivning |
| --- | --- |
| obj | Objektet att jämföra med det aktuella objektet. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Hämtar adressrad 1. Adressrad 1 innehåller gatunamn, husnummer eller postbox. Att ställa in detta fält sätter adresstypen till AddressType.COMBINED_ELEMENTS om den inte redan är AddressType.STRUCTURED, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för adresser med kombinerade element och är valfritt.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Hämtar adressrad 2. Adressrad 2 innehåller postnummer och ort. Att ställa in detta fält sätter adresstypen till AddressType.COMBINED_ELEMENTS om den inte redan är AddressType.STRUCTURED, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för adresser med kombinerade element. För denna typ är det obligatoriskt.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Hämtar den tvåbokstaviga ISO-landkoden. Landkoden är obligatorisk om inte hela adressen innehåller null eller tomma värden.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Hämtar husnumret. Att ställa in detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser och är valfritt.

**Returns:** The house number.

### getName() {#getname}

Hämtar namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Hämtar postnumret. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

**Returns:** The postal code.

### getStreet() {#getstreet}

Hämtar gatan. Gatan måste anges utan husnummer. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser och är valfritt.

**Returns:** The street.

### getTown() {#gettown}

Hämtar orten eller staden. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

**Returns:** The town or city.

### getType() {#gettype}

Hämtar adresstypen. Adresstypen sätts automatiskt genom att antingen ange gata / husnummer eller adressrad 1 och 2. Innan fälten sätts är adresstypen Undetermined. Om fält av båda typerna anges blir adresstypen Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Hämtar hash‑koden för detta objekt.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Anger adressrad 1. Adressrad 1 innehåller gatunamn, husnummer eller postbox. Att ange detta fält sätter adresstypen till AddressType.COMBINED_ELEMENTS om den inte redan är AddressType.STRUCTURED, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för adresser med kombinerade element och är valfritt.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Adressrad 1. |

### setAddressLine2(value:) {#setaddressline2}

Anger adressrad 2. Adressrad 2 innehåller postnummer och ort. Att ange detta fält sätter adresstypen till AddressType.COMBINED_ELEMENTS om den inte redan är AddressType.STRUCTURED, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för adresser med kombinerade element. För denna typ är det obligatoriskt.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Adressrad 2. |

### setCountryCode(value) {#setcountrycode}

Anger den tvåbokstaviga ISO-landskoden. Landskoden är obligatorisk såvida inte hela adressen innehåller null- eller tomma värden.

| Parameter | Beskrivning |
| --- | --- |
| värde | ISO-landskoden. |

### setHouseNo(value:) {#sethouseno}

Anger husnumret. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser och är valfritt.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Husnumret. |

### setName(value:) {#setname}

Ställer in namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Namnet. |

### setPostalCode(value) {#setpostalcode}

Anger postnumret. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

| Parameter | Beskrivning |
| --- | --- |
| värde | Postnumret. |

### setStreet(value:) {#setstreet}

Anger gatan. Gatan måste anges utan husnummer. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser och är valfritt.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Gatan. |

### setTown(value) {#settown}

Anger orten eller staden. Att ange detta fält sätter adresstypen till AddressType.STRUCTURED om den inte redan är AddressType.COMBINED_ELEMENTS, i så fall blir den AddressType.CONFLICTING. Detta fält används endast för strukturerade adresser. För denna typ är det obligatoriskt.

| Parameter | Beskrivning |
| --- | --- |
| värde | Orten eller staden. |

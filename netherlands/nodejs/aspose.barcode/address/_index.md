---
title: "Adres"
linktitle: "Adres"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Adres van schuldeiser of schuldenaar."
type: docs
weight: 10
url: /nl/nodejs/aspose.barcode/address/
---

## Address class

Adres van schuldeiser of schuldenaar. U kunt ofwel straat, huisnummer, postcode en plaats (type gestructureerd adres) of adresregel 1 en 2 (type gecombineerde adresselementen) instellen. Het type wordt automatisch ingesteld zodra een van deze velden is ingevuld. Voor het instellen van de velden is het adrestype onbepaald. Als velden van beide typen zijn ingevuld, ontstaat een conflicterend adrestype. Naam en landcode moeten altijd worden ingesteld tenzij alle velden leeg zijn.

```js
new Address()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [clear()](#clear) | Wis alle velden en stel het type in op AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [getAddressLine1()](#getaddressline1) | Haalt adresregel 1 op. Adresregel 1 bevat straatnaam, huisnummer of postbus. Het instellen van dit veld stelt de addr |
| [getAddressLine2()](#getaddressline2) | Haalt adresregel 2 op. Adresregel 2 bevat postcode en plaats. Het instellen van dit veld stelt het adrestype in op Addre |
| [getCountryCode()](#getcountrycode) | Haalt de tweeletterige ISO-landcode op. De landcode is verplicht tenzij het volledige adres null of lege waarde bevat |
| [getHouseNo()](#gethouseno) | Haalt het huisnummer op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressTyp is |
| [getName()](#getname) | Haalt de naam op, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [getPostalCode()](#getpostalcode) | Haalt de postcode op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType is |
| [getStreet()](#getstreet) | Haalt de straat op. De straat moet worden opgegeven zonder huisnummer. Het instellen van dit veld stelt het adrestype in op AddressT |
| [getTown()](#gettown) | Haalt de plaats of stad op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressTyp is |
| [getType()](#gettype) | Haalt het adrestype op. Het adrestype wordt automatisch ingesteld door ofwel straat / huisnummer of adresregel 1 a |
| [hashCode()](#hashcode) | Haalt de hashcode op voor deze instantie. |
| [setAddressLine1(value:)](#setaddressline1) | Stelt adresregel 1 in. Adresregel 1 bevat straatnaam, huisnummer of postbus. Het instellen van dit veld stelt de addr |
| [setAddressLine2(value:)](#setaddressline2) | Stelt de adresregel 2 in. Adresregel 2 bevat postcode en plaats. Het instellen van dit veld stelt het adrestype in op Addre |
| [setCountryCode(value)](#setcountrycode) | Stelt de tweeletterige ISO-landcode in. De landcode is verplicht tenzij het volledige adres null of emtpy val bevat. |
| [setHouseNo(value:)](#sethouseno) | Stelt het huisnummer in. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressTyp is. |
| [setName(value:)](#setname) | Stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [setPostalCode(value)](#setpostalcode) | Stelt de postcode in. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType is. |
| [setStreet(value:)](#setstreet) | Stelt de straat in. De straat moet worden gespecificeerd zonder huisnummer. Het instellen van dit veld stelt het adrestype in op AddressT |
| [setTown(value)](#settown) | Stelt de stad of plaats in. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressTyp is. |

### clear() {#clear}

Wis alle velden en stel het type in op AddressType.UNDETERMINED.

### equals(obj) {#equals}

Bepaalt of het opgegeven object gelijk is aan het huidige object.

| Parameter | Beschrijving |
| --- | --- |
| obj | Het object om te vergelijken met het huidige object. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Haalt de adresregel 1 op. Adresregel 1 bevat straatnaam, huisnummer of P.O. box. Het instellen van dit veld stelt het adrestype in op AddressType.COMBINED_ELEMENTS tenzij het al AddressType.STRUCTURED is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor adressen met gecombineerde elementen en is optioneel.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Haalt de adresregel 2 op. Adresregel 2 bevat postcode en plaats. Het instellen van dit veld stelt het adrestype in op AddressType.COMBINED_ELEMENTS tenzij het al AddressType.STRUCTURED is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor adressen met gecombineerde elementen. Voor dit type is het verplicht.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Haalt de tweeletterige ISO-landcode op. De landcode is verplicht tenzij het volledige adres null of lege waarden bevat.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Haalt het huisnummer op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

**Returns:** The house number.

### getName() {#getname}

Haalt de naam op, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Haalt de postcode op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

**Returns:** The postal code.

### getStreet() {#getstreet}

Haalt de straat op. De straat moet worden gespecificeerd zonder huisnummer. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

**Returns:** The street.

### getTown() {#gettown}

Haalt de stad of plaats op. Het instellen van dit veld stelt het adrestype in op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

**Returns:** The town or city.

### getType() {#gettype}

Haalt het adrestype op. Het adrestype wordt automatisch ingesteld door ofwel de straat / het huisnummer of adresregel 1 en 2 in te stellen. Voor het instellen van de velden is het adrestype Onbepaald. Als velden van beide typen worden ingesteld, wordt het adrestype Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Haalt de hashcode op voor deze instantie.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Stelt de adresregel 1 in. Adresregel 1 bevat straatnaam, huisnummer of P.O. box. Het instellen van dit veld stelt het adrestype in op AddressType.COMBINED_ELEMENTS tenzij het al AddressType.STRUCTURED is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor adressen met gecombineerde elementen en is optioneel.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De adresregel 1. |

### setAddressLine2(value:) {#setaddressline2}

Stelt de adresregel 2 in. Adresregel 2 bevat postcode en plaats. Het instellen van dit veld stelt het adrestype in op AddressType.COMBINED_ELEMENTS tenzij het al AddressType.STRUCTURED is, in welk geval het AddressType.CONFLICTING wordt. Dit veld wordt alleen gebruikt voor adressen met gecombineerde elementen. Voor dit type is het verplicht.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De adresregel 2. |

### setCountryCode(value) {#setcountrycode}

Stelt de tweeletterige ISO-landcode in. De landcode is verplicht tenzij het volledige adres null of lege waarden bevat.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De ISO-landcode. |

### setHouseNo(value:) {#sethouseno}

Stelt het huisnummer in. Het instellen van dit veld zet het adrestype op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in dat geval wordt het AddressType.CONFLICTING. Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | Het huisnummer. |

### setName(value:) {#setname}

Stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De naam. |

### setPostalCode(value) {#setpostalcode}

Stelt de postcode in. Het instellen van dit veld zet het adrestype op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in dat geval wordt het AddressType.CONFLICTING. Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De postcode. |

### setStreet(value:) {#setstreet}

Stelt de straat in. De straat moet worden opgegeven zonder huisnummer. Het instellen van dit veld zet het adrestype op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in dat geval wordt het AddressType.CONFLICTING. Dit veld wordt alleen gebruikt voor gestructureerde adressen en is optioneel.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De straat. |

### setTown(value) {#settown}

Stelt de plaats of stad in. Het instellen van dit veld zet het adrestype op AddressType.STRUCTURED tenzij het al AddressType.COMBINED_ELEMENTS is, in dat geval wordt het AddressType.CONFLICTING. Dit veld wordt alleen gebruikt voor gestructureerde adressen. Voor dit type is het verplicht.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De plaats of stad. |

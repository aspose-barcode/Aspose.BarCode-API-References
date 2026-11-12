---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Verplichte elementen (velden) van de kaart"
type: docs
weight: 590
url: /nl/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Verplichte elementen (velden) van de kaart

```js
new MandatoryFields()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, stadsgedeelte van het kaartinhouderadres, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, postcodegedeelte van het kaartinhouderadres in de VS en Canada. Als het achterste gedeelte van de postcode in |
| [getAddressState()](#getaddressstate) | DAJ, staatgedeelte van het kaartinhouderadres, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, straatgedeelte van het kaartinhouderadres, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Land waarin DL/ID wordt uitgegeven. VS = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Het nummer dat door de uitgevende autoriteit is toegewezen of berekend, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Nummer moet een specifiek document dat aan die klant is uitgegeven uniek identificeren ten opzichte van andere die mogelijk zijn uitgegeven i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Jurisdictiespecifieke goedkeuringscodes, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Kleur van de ogen van de kaarthouder. (ANSI D-20 codes). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Familienaam van de kaarthouder, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [getFirstName()](#getfirstname) | DAC, Voornaam van de kaarthouder, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [getHeight()](#getheight) | DAU, Lengte van de kaarthouder. Inches (in): aantal inches gevolgd door " in" bijv. 6'1'' = "073 in" Centimeters(cm): aantal |
| [getMiddleName()](#getmiddlename) | DAD, Tussenvoegsel(s) van de kaarthouder. Bij meerdere tussenvoegsels moeten ze gescheiden worden door een komma ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Jurisdictiespecifieke restrictiecodes, DL, V12ANS |
| [getSex()](#getsex) | DBC, Geslacht van de kaarthouder. 1 = man, 2 = vrouw, 9 = niet gespecificeerd, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Jurisdictiespecifieke voertuigklasse / groepscode, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, stadsgedeelte van het kaartinhouderadres, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, postcodegedeelte van het kaartinhouderadres in de VS en Canada. Als het achterste gedeelte van de postcode in |
| [setAddressState()](#setaddressstate) | DAJ, staatgedeelte van het kaartinhouderadres, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, straatgedeelte van het kaartinhouderadres, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Land waarin DL/ID wordt uitgegeven. VS = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Het nummer dat door de uitgevende autoriteit is toegewezen of berekend, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Nummer moet een specifiek document dat aan die klant is uitgegeven uniek identificeren ten opzichte van andere die mogelijk zijn uitgegeven i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Jurisdictiespecifieke goedkeuringscodes, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Kleur van de ogen van de kaarthouder. (ANSI D-20 codes). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Familienaam van de kaarthouder, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [setFirstName()](#setfirstname) | DAC, Voornaam van de kaarthouder, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [setHeight()](#setheight) | DAU, Lengte van de kaarthouder. Inches (in): aantal inches gevolgd door " in" bijv. 6'1'' = "073 in" Centimeters(cm): aantal |
| [setMiddleName()](#setmiddlename) | DAD, Tussenvoegsel(s) van de kaarthouder. Bij meerdere tussenvoegsels moeten ze gescheiden worden door een komma ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Jurisdictiespecifieke restrictiecodes, DL, V12ANS |
| [setSex()](#setsex) | DBC, Geslacht van de kaarthouder. 1 = man, 2 = vrouw, 9 = niet gespecificeerd, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Jurisdictiespecifieke voertuigklasse / groepscode, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, stadsgedeelte van het kaartinhouderadres, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Postcodegedeelte van het adres van de kaarthouder in de VS en Canada. Als het achterste gedeelte van de postcode in de VS niet bekend is, worden nullen gebruikt om het achterste cijferreeks tot 9 cijfers aan te vullen, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, staatgedeelte van het kaartinhouderadres, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, straatgedeelte van het kaartinhouderadres, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Land waarin DL/ID wordt uitgegeven. VS = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Het nummer dat door de uitgevende autoriteit is toegewezen of berekend, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Nummer moet een specifiek document dat aan die klant is uitgegeven uniek identificeren ten opzichte van andere die in het verleden zijn uitgegeven. Dit nummer kan meerdere doeleinden dienen, zoals documentdiscriminatie, auditinformatie‑nummer en/of voorraadbeheer, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Jurisdictiespecifieke goedkeuringscodes, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Kleur van de ogen van de kaarthouder. (ANSI D-20 codes). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Familienaam van de kaarthouder, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Voornaam van de kaarthouder, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Lengte van de kaarthouder. Inches (in): aantal inches gevolgd door " in" bijv. 6'1'' = "073 in" Centimeters(cm): aantal centimeters gevolgd door " cm" bijv. 181 centimeters="181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Tussenvoegsel(s) van de kaarthouder. Bij meerdere tussenvoegsels moeten ze gescheiden worden door een komma ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Jurisdictiespecifieke restrictiecodes, DL, V12ANS

### getSex() {#getsex}

DBC, Geslacht van de kaarthouder. 1 = man, 2 = vrouw, 9 = niet gespecificeerd, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Jurisdictiespecifieke voertuigklasse / groepscode, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, stadsgedeelte van het kaartinhouderadres, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Postcodegedeelte van het adres van de kaarthouder in de VS en Canada. Als het achterste gedeelte van de postcode in de VS niet bekend is, worden nullen gebruikt om het achterste cijferreeks tot 9 cijfers aan te vullen, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, staatgedeelte van het kaartinhouderadres, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, straatgedeelte van het kaartinhouderadres, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Land waarin DL/ID wordt uitgegeven. VS = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Het nummer dat door de uitgevende autoriteit is toegewezen of berekend, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Datum waarop het document is uitgegeven, MMDDCCYY voor VS, CCYYMMDD voor Canada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Nummer moet een specifiek document dat aan die klant is uitgegeven uniek identificeren ten opzichte van andere die in het verleden zijn uitgegeven. Dit nummer kan meerdere doeleinden dienen, zoals documentdiscriminatie, auditinformatie‑nummer en/of voorraadbeheer, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Jurisdictiespecifieke goedkeuringscodes, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Kleur van de ogen van de kaarthouder. (ANSI D-20 codes). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Familienaam van de kaarthouder, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Voornaam van de kaarthouder, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Lengte van de kaarthouder. Inches (in): aantal inches gevolgd door " in" bijv. 6'1'' = "073 in" Centimeters(cm): aantal centimeters gevolgd door " cm" bijv. 181 centimeters="181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Tussenvoegsel(s) van de kaarthouder. Bij meerdere tussenvoegsels moeten ze gescheiden worden door een komma ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Een code die aangeeft of een veld is afgekapt (T), niet is afgekapt (N), of onbekend of het is afgekapt (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Jurisdictiespecifieke restrictiecodes, DL, V12ANS

### setSex() {#setsex}

DBC, Geslacht van de kaarthouder. 1 = man, 2 = vrouw, 9 = niet gespecificeerd, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Jurisdictiespecifieke voertuigklasse / groepscode, DL, V6ANS

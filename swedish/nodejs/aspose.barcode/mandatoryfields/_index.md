---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Obligatoriska element (fält) på kortet"
type: docs
weight: 590
url: /sv/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Obligatoriska element (fält) på kortet

```js
new MandatoryFields()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, staddel av kortägarens adress, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den efterföljande delen av postnumret i |
| [getAddressState()](#getaddressstate) | DAJ, Del för delstat i kortinnehavarens adress, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, Gatuadressdel av kortinnehavarens adress, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Numret som tilldelas eller beräknas av utfärdande myndighet, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [getFirstName()](#getfirstname) | DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [getHeight()](#getheight) | DAU, Höjd på kortinnehavaren. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal |
| [getMiddleName()](#getmiddlename) | DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS |
| [getSex()](#getsex) | DBC, Kön på kortinnehavaren. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, staddel av kortägarens adress, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den efterföljande delen av postnumret i |
| [setAddressState()](#setaddressstate) | DAJ, Del för delstat i kortinnehavarens adress, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, Gatuadressdel av kortinnehavarens adress, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Numret som tilldelas eller beräknas av utfärdande myndighet, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [setFirstName()](#setfirstname) | DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [setHeight()](#setheight) | DAU, Höjd på kortinnehavaren. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal |
| [setMiddleName()](#setmiddlename) | DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS |
| [setSex()](#setsex) | DBC, Kön på kortinnehavaren. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, staddel av kortägarens adress, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den efterföljande delen av postnumret i USA inte är känd, kommer nollor att användas för att fylla den efterföljande siffrasekvensen upp till 9 siffror, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, Del för delstat i kortinnehavarens adress, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, Gatuadressdel av kortinnehavarens adress, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Numret som tilldelas eller beräknas av utfärdande myndighet, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats tidigare. Detta nummer kan användas för flera ändamål såsom dokumentdifferentiering, revisionsinformationsnummer och/eller lagerkontroll, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Höjd på kortinnehavaren. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal centimeter följt av " cm" t.ex. 181 centimeter = "181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, en kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS

### getSex() {#getsex}

DBC, Kön på kortinnehavaren. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, staddel av kortägarens adress, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den efterföljande delen av postnumret i USA inte är känd, kommer nollor att användas för att fylla den efterföljande siffrasekvensen upp till 9 siffror, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, Del för delstat i kortinnehavarens adress, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, Gatuadressdel av kortinnehavarens adress, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Numret som tilldelas eller beräknas av utfärdande myndighet, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats tidigare. Detta nummer kan användas för flera ändamål såsom dokumentdifferentiering, revisionsinformationsnummer och/eller lagerkontroll, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Höjd på kortinnehavaren. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal centimeter följt av " cm" t.ex. 181 centimeter = "181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, en kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS

### setSex() {#setsex}

DBC, Kön på kortinnehavaren. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS

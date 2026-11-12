---
title: "Pflichtfelder"
linktitle: "Pflichtfelder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Obligatorische Elemente (Felder) der Karte"
type: docs
weight: 590
url: /de/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Obligatorische Elemente (Felder) der Karte

```js
new MandatoryFields()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in |
| [getAddressState()](#getaddressstate) | DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die möglicherweise ausgestellt wurden, unterscheiden i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Familienname des Karteninhabers, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [getFirstName()](#getfirstname) | DAC, Vorname des Karteninhabers, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [getHeight()](#getheight) | DAU, Größe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in", z.B. 6'1'' = "073 in" Zentimeter (cm): Zahl |
| [getMiddleName()](#getmiddlename) | DAD, Mittelname(n) des Karteninhabers. Bei mehreren Mittelnamen sollen sie durch ein Komma "," getrennt werden. , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Jurisdiktionsspezifische Beschränkungscodes, DL, V12ANS |
| [getSex()](#getsex) | DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Jurisdiktionsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in |
| [setAddressState()](#setaddressstate) | DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die möglicherweise ausgestellt wurden, unterscheiden i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Familienname des Karteninhabers, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [setFirstName()](#setfirstname) | DAC, Vorname des Karteninhabers, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [setHeight()](#setheight) | DAU, Größe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in", z.B. 6'1'' = "073 in" Zentimeter (cm): Zahl |
| [setMiddleName()](#setmiddlename) | DAD, Mittelname(n) des Karteninhabers. Bei mehreren Mittelnamen sollen sie durch ein Komma "," getrennt werden. , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Jurisdiktionsspezifische Beschränkungscodes, DL, V12ANS |
| [setSex()](#setsex) | DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Jurisdiktionsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in den USA nicht bekannt ist, werden Nullen verwendet, um den nachfolgenden Zahlenblock bis zu 9 Stellen aufzufüllen, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. Diese Nummer kann mehreren Zwecken dienen, wie Dokumentenunterscheidung, Prüfungsinformationsnummer und/oder Bestandskontrolle, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Familienname des Karteninhabers, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Vorname des Karteninhabers, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Höhe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in", z.B. 6'1'' = "073 in" Zentimeter (cm): Zahl der Zentimeter gefolgt von " cm", z.B. 181 Zentimeter = "181 cm", DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Zweiter Vorname(n) des Karteninhabers. Im Falle mehrerer zweiter Vornamen sollen sie durch ein Komma "," getrennt werden., DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Jurisdiktionsspezifische Beschränkungscodes, DL, V12ANS

### getSex() {#getsex}

DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Jurisdiktionsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in den USA nicht bekannt ist, werden Nullen verwendet, um den nachfolgenden Zahlenblock bis zu 9 Stellen aufzufüllen, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. Diese Nummer kann mehreren Zwecken dienen, wie Dokumentenunterscheidung, Prüfungsinformationsnummer und/oder Bestandskontrolle, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Familienname des Karteninhabers, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Vorname des Karteninhabers, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Höhe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in", z.B. 6'1'' = "073 in" Zentimeter (cm): Zahl der Zentimeter gefolgt von " cm", z.B. 181 Zentimeter = "181 cm", DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Zweiter Vorname(n) des Karteninhabers. Im Falle mehrerer zweiter Vornamen sollen sie durch ein Komma "," getrennt werden., DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Ein Code, der angibt, ob ein Feld abgeschnitten wurde (T), nicht abgeschnitten wurde (N) oder unbekannt ist, ob es abgeschnitten wurde (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Jurisdiktionsspezifische Beschränkungscodes, DL, V12ANS

### setSex() {#setsex}

DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Jurisdiktionsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS

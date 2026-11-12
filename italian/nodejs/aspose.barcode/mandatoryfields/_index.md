---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Elementi obbligatori (campi) della carta"
type: docs
weight: 590
url: /it/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Elementi obbligatori (campi) della carta

```js
new MandatoryFields()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. Se la parte finale del codice postale in |
| [getAddressState()](#getaddressstate) | DAJ, parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Paese in cui viene rilasciato il DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Il numero deve identificare in modo univoco un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Cognome del titolare della carta, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [getFirstName()](#getfirstname) | DAC, Nome del titolare della carta, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [getHeight()](#getheight) | DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da \" in\" es. 6'1'' = \"073 in\" Centimetri (cm): numero |
| [getMiddleName()](#getmiddlename) | DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola \",\". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS |
| [getSex()](#getsex) | DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Codice di classe/gruppo veicolo specifico della giurisdizione, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. Se la parte finale del codice postale in |
| [setAddressState()](#setaddressstate) | DAJ, parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Paese in cui viene rilasciato il DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Il numero deve identificare in modo univoco un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Cognome del titolare della carta, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [setFirstName()](#setfirstname) | DAC, Nome del titolare della carta, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [setHeight()](#setheight) | DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da \" in\" es. 6'1'' = \"073 in\" Centimetri (cm): numero |
| [setMiddleName()](#setmiddlename) | DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola \",\". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS |
| [setSex()](#setsex) | DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Codice di classe/gruppo veicolo specifico della giurisdizione, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e in Canada. Se la parte finale del codice postale negli Stati Uniti non è nota, verranno usati zeri per completare la sequenza finale di numeri fino a 9 cifre, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Paese in cui viene rilasciato il DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Il numero deve identificare in modo univoco un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi in passato. Questo numero può servire a molteplici scopi di discriminazione del documento, numero di informazione di audit e/o controllo dell'inventario, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Cognome del titolare della carta, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Nome del titolare della carta, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da \" in\" es. 6'1'' = \"073 in\" Centimetri (cm): numero di centimetri seguito da \" cm\" es. 181 centimetri=\"181 cm\" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola \",\". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS

### getSex() {#getsex}

DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Codice di classe/gruppo veicolo specifico della giurisdizione, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e in Canada. Se la parte finale del codice postale negli Stati Uniti non è nota, verranno usati zeri per completare la sequenza finale di numeri fino a 9 cifre, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Paese in cui viene rilasciato il DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Data di emissione del documento, MMDDCCYY per gli Stati Uniti, CCYYMMDD per il Canada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Il numero deve identificare in modo univoco un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi in passato. Questo numero può servire a molteplici scopi di discriminazione del documento, numero di informazione di audit e/o controllo dell'inventario, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Cognome del titolare della carta, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Nome del titolare della carta, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da \" in\" es. 6'1'' = \"073 in\" Centimetri (cm): numero di centimetri seguito da \" cm\" es. 181 centimetri=\"181 cm\" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola \",\". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N), o se lo stato di troncamento è sconosciuto (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS

### setSex() {#setsex}

DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Codice di classe/gruppo veicolo specifico della giurisdizione, DL, V6ANS

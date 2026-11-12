---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Éléments obligatoires (champs) de la carte"
type: docs
weight: 590
url: /fr/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

Éléments obligatoires (champs) de la carte

```js
new MandatoryFields()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, partie Ville de l'adresse du titulaire, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, partie code postal de l'adresse du titulaire aux États‑Unis et au Canada. Si la partie finale du code postal dans |
| [getAddressState()](#getaddressstate) | DAJ, partie État de l'adresse du titulaire, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, partie Rue de l'adresse du titulaire, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, Pays dans lequel le DL/ID est délivré. États‑Unis = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, Le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, Codes d'approbation spécifiques à la juridiction, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, Nom de famille du titulaire de la carte, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [getFirstName()](#getfirstname) | DAC, Prénom du titulaire de la carte, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [getHeight()](#getheight) | DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres (cm) : nombre |
| [getMiddleName()](#getmiddlename) | DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs prénoms, ils doivent être séparés par une virgule ",". , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, Codes de restrictions spécifiques à la juridiction, DL, V12ANS |
| [getSex()](#getsex) | DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, Code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, partie Ville de l'adresse du titulaire, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, partie code postal de l'adresse du titulaire aux États‑Unis et au Canada. Si la partie finale du code postal dans |
| [setAddressState()](#setaddressstate) | DAJ, partie État de l'adresse du titulaire, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, partie Rue de l'adresse du titulaire, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, Pays dans lequel le DL/ID est délivré. États‑Unis = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, Le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, Codes d'approbation spécifiques à la juridiction, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, Nom de famille du titulaire de la carte, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [setFirstName()](#setfirstname) | DAC, Prénom du titulaire de la carte, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [setHeight()](#setheight) | DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres (cm) : nombre |
| [setMiddleName()](#setmiddlename) | DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs prénoms, ils doivent être séparés par une virgule ",". , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, Codes de restrictions spécifiques à la juridiction, DL, V12ANS |
| [setSex()](#setsex) | DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, Code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, partie Ville de l'adresse du titulaire, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, Portion du code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. Si la partie finale du code postal aux États‑Unis est inconnue, des zéros seront utilisés pour compléter la série de chiffres jusqu'à 9 chiffres, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, partie État de l'adresse du titulaire, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, partie Rue de l'adresse du titulaire, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, Pays dans lequel le DL/ID est délivré. États‑Unis = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, Le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés dans le passé. Ce numéro peut servir à plusieurs fins : discrimination de documents, numéro d'information d'audit et/ou contrôle d'inventaire, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, Codes d'approbation spécifiques à la juridiction, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, Nom de famille du titulaire de la carte, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, Prénom du titulaire de la carte, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres (cm) : nombre de centimètres suivi de " cm" ex. 181 centimètres="181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs prénoms, ils doivent être séparés par une virgule ",". , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, Codes de restrictions spécifiques à la juridiction, DL, V12ANS

### getSex() {#getsex}

DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, Code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, partie Ville de l'adresse du titulaire, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, Portion du code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. Si la partie finale du code postal aux États‑Unis est inconnue, des zéros seront utilisés pour compléter la série de chiffres jusqu'à 9 chiffres, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, partie État de l'adresse du titulaire, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, partie Rue de l'adresse du titulaire, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, Pays dans lequel le DL/ID est délivré. États‑Unis = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, Le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, Date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés dans le passé. Ce numéro peut servir à plusieurs fins : discrimination de documents, numéro d'information d'audit et/ou contrôle d'inventaire, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, Codes d'approbation spécifiques à la juridiction, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, Nom de famille du titulaire de la carte, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, Prénom du titulaire de la carte, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres (cm) : nombre de centimètres suivi de " cm" ex. 181 centimètres="181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs prénoms, ils doivent être séparés par une virgule ",". , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, Un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, Codes de restrictions spécifiques à la juridiction, DL, V12ANS

### setSex() {#setsex}

DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, Code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS

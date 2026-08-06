---
title: USADriveIdCodetext.MandatoryFields
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Champs des éléments obligatoires de la carte
type: docs
weight: 10
url: /fr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Éléments obligatoires (champs) de la carte
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, partie ville de l'adresse du titulaire de la carte, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, partie code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. |
| [getAddressState()](#getAddressState--) | DAJ, partie État de l'adresse du titulaire de la carte, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, pays où le DL/ID est délivré. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés par le passé. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, codes d'endossement spécifiques à la juridiction, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, couleur des yeux du titulaire de la carte. |
| [getFamilyName()](#getFamilyName--) | DCS, nom de famille du titulaire de la carte, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, prénom du titulaire de la carte, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, taille du titulaire de la carte. |
| [getMiddleName()](#getMiddleName--) | DAD, deuxième(s) prénom(s) du titulaire de la carte. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, codes de restrictions spécifiques à la juridiction, DL, V12ANS |
| [getSex()](#getSex--) | DBC, sexe du titulaire de la carte. |
| [getVehicleClass()](#getVehicleClass--) | DCA, code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, partie ville de l'adresse du titulaire de la carte, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, partie code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, partie État de l'adresse du titulaire de la carte, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, pays où le DL/ID est délivré. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui pourraient avoir été délivrés par le passé. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, codes d'endossement spécifiques à la juridiction, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, couleur des yeux du titulaire de la carte. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, nom de famille du titulaire de la carte, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, prénom du titulaire de la carte, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, taille du titulaire de la carte. |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, deuxième(s) prénom(s) du titulaire de la carte. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, codes de restrictions spécifiques à la juridiction, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, sexe du titulaire de la carte. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, partie ville de l'adresse du titulaire de la carte, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, partie code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. Si la partie finale du code postal aux États‑Unis n'est pas connue, des zéros seront utilisés pour remplir la suite de chiffres jusqu'à 9 chiffres, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, partie État de l'adresse du titulaire de la carte, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG, Pays dans lequel le DL/ID est délivré. U.S. = USA, Canada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui ont pu être délivrés dans le passé. Ce numéro peut servir à plusieurs fins de discrimination de documents, de numéro d'information d'audit et/ou de contrôle d'inventaire, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, codes d'endossement spécifiques à la juridiction, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, nom de famille du titulaire de la carte, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, prénom du titulaire de la carte, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres(cm) : nombre de centimètres suivi de " cm" ex. 181 centimètres="181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs deuxièmes prénoms, ils doivent être séparés par une virgule ",". , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, codes de restrictions spécifiques à la juridiction, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, partie ville de l'adresse du titulaire de la carte, DL/ID, V20ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, partie code postal de l'adresse du titulaire de la carte aux États‑Unis et au Canada. Si la partie finale du code postal aux États‑Unis n'est pas connue, des zéros seront utilisés pour remplir la suite de chiffres jusqu'à 9 chiffres, DL/ID, F11ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, partie État de l'adresse du titulaire de la carte, DL/ID, F2A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, partie rue de l'adresse du titulaire de la carte, DL/ID, V35ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Pays dans lequel le DL/ID est délivré. U.S. = USA, Canada = CAN, DL/ID, F3A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, le numéro attribué ou calculé par l'autorité émettrice, DL/ID, V25ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, date à laquelle le document a été délivré, MMDDCCYY pour les États‑Unis, CCYYMMDD pour le Canada, DL/ID, F8N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Le numéro doit identifier de manière unique un document particulier délivré à ce client parmi d'autres qui ont pu être délivrés dans le passé. Ce numéro peut servir à plusieurs fins de discrimination de documents, de numéro d'information d'audit et/ou de contrôle d'inventaire, DL/ID, V25ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, codes d'endossement spécifiques à la juridiction, DL, V5ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Couleur des yeux du titulaire de la carte. (codes ANSI D-20). DL/ID, F3A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, nom de famille du titulaire de la carte, DL/ID, V40ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, prénom du titulaire de la carte, DL/ID, V40ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Taille du titulaire de la carte. Pouces (in) : nombre de pouces suivi de " in" ex. 6'1'' = "073 in" Centimètres(cm) : nombre de centimètres suivi de " cm" ex. 181 centimètres="181 cm" , DL/ID, F6ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Deuxième(s) prénom(s) du titulaire de la carte. Dans le cas de plusieurs deuxièmes prénoms, ils doivent être séparés par une virgule ",". , DL/ID, V40ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, un code indiquant si un champ a été tronqué (T), n'a pas été tronqué (N), ou si l'on ignore s'il a été tronqué (U), DL/ID, F1A

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, codes de restrictions spécifiques à la juridiction, DL, V12ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Sexe du titulaire de la carte. 1 = homme, 2 = femme, 9 = non spécifié, DL/ID, F1N

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, code de classe / groupe de véhicule spécifique à la juridiction, DL, V6ANS

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


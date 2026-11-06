---
title: "USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: "Obligatorische Elementfelder der Karte"
type: docs
weight: 10
url: /de/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Obligatorische Elemente (Felder) der Karte
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. |
| [getAddressState()](#getAddressState--) | DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Land, in dem DL/ID ausgestellt wird. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS |
| [getExpirationDate()](#getExpirationDate--) | DBA, Ablaufdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [getEyeColor()](#getEyeColor--) | DAY, Augenfarbe des Karteninhabers. |
| [getFamilyName()](#getFamilyName--) | DCS, Nachname des Karteninhabers, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Vorname des Karteninhabers, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Körpergröße des Karteninhabers. |
| [getIssueDate()](#getIssueDate--) | DBD, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [getMiddleName()](#getMiddleName--) | DAD, Zweiter Vorname(n) des Karteninhabers. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Rechtsgebietsspezifische Beschränkungscodes, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Geschlecht des Karteninhabers. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Rechtsgebietsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Land, in dem DL/ID ausgestellt wird. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Die Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS |
| [setExpirationDate(LocalDate value)](#setExpirationDate-java.time.LocalDate-) | DBA, Ablaufdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Augenfarbe des Karteninhabers. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Nachname des Karteninhabers, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Vorname des Karteninhabers, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Körpergröße des Karteninhabers. |
| [setIssueDate(LocalDate value)](#setIssueDate-java.time.LocalDate-) | DBD, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Zweiter Vorname(n) des Karteninhabers. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Rechtsgebietsspezifische Beschränkungscodes, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Geschlecht des Karteninhabers. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Rechtsgebietsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in den USA nicht bekannt ist, werden Nullen verwendet, um die nachfolgenden Ziffern bis zu 9 Stellen aufzufüllen, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS

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


DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. Diese Nummer kann mehrere Zwecke erfüllen, z. B. Dokumentenidentifikation, Prüfungsinformationsnummer und/oder Bestandskontrolle, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS

**Returns:**
java.lang.String
### getExpirationDate() {#getExpirationDate--}
```
public final LocalDate getExpirationDate()
```


DBA, Ablaufdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Nachname des Karteninhabers, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Vorname des Karteninhabers, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Größe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in" z. B. 6'1'' = "073 in" Zentimeter (cm): Zahl der Zentimeter gefolgt von " cm" z. B. 181 Zentimeter="181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getIssueDate() {#getIssueDate--}
```
public final LocalDate getIssueDate()
```


DBD, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Zweiter Vorname(n) des Karteninhabers. Im Falle mehrerer zweiter Vornamen sollen sie durch ein Komma "," getrennt werden., DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Rechtsgebietsspezifische Beschränkungscodes, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Rechtsgebietsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS

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


DAI, Stadtanteil der Karteninhaberadresse, DL/ID, V20ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Postleitzahlanteil der Karteninhaberadresse in den USA und Kanada. Wenn der nachfolgende Teil der Postleitzahl in den USA nicht bekannt ist, werden Nullen verwendet, um die nachfolgenden Ziffern bis zu 9 Stellen aufzufüllen, DL/ID, F11ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Bundesstaatanteil der Karteninhaberadresse, DL/ID, F2A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Straßenanteil der Karteninhaberadresse, DL/ID, V35ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Land, in dem DL/ID ausgestellt wird. USA = USA, Kanada = CAN, DL/ID, F3A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Die von der ausstellenden Behörde zugewiesene oder berechnete Nummer, DL/ID, V25ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Nummer muss ein bestimmtes, dem Kunden ausgestelltes Dokument eindeutig von anderen, die in der Vergangenheit ausgestellt wurden, unterscheiden. Diese Nummer kann mehrere Zwecke erfüllen, z. B. Dokumentenidentifikation, Prüfungsinformationsnummer und/oder Bestandskontrolle, DL/ID, V25ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Jurisdiktionsspezifische Beglaubigungscodes, DL, V5ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setExpirationDate(LocalDate value) {#setExpirationDate-java.time.LocalDate-}
```
public final void setExpirationDate(LocalDate value)
```


DBA, Ablaufdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Augenfarbe des Karteninhabers. (ANSI D-20 Codes). DL/ID, F3A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Nachname des Karteninhabers, DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Vorname des Karteninhabers, DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Größe des Karteninhabers. Zoll (in): Zahl der Zoll gefolgt von " in" z. B. 6'1'' = "073 in" Zentimeter (cm): Zahl der Zentimeter gefolgt von " cm" z. B. 181 Zentimeter="181 cm" , DL/ID, F6ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setIssueDate(LocalDate value) {#setIssueDate-java.time.LocalDate-}
```
public final void setIssueDate(LocalDate value)
```


DBD, Ausstellungsdatum des Dokuments, MMDDCCYY für die USA, CCYYMMDD für Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Zweiter Vorname(n) des Karteninhabers. Im Falle mehrerer zweiter Vornamen sollen sie durch ein Komma "," getrennt werden., DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Ein Code, der angibt, ob ein Feld gekürzt wurde (T), nicht gekürzt wurde (N) oder unbekannt ist, ob es gekürzt wurde (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Rechtsgebietsspezifische Beschränkungscodes, DL, V12ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Geschlecht des Karteninhabers. 1 = männlich, 2 = weiblich, 9 = nicht angegeben, DL/ID, F1N

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Rechtsgebietsspezifischer Fahrzeugklasse-/Gruppencode, DL, V6ANS

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


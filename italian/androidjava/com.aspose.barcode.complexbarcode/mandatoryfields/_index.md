---
title: USADriveIdCodetext.MandatoryFields
second_title: Aspose.BarCode per Android via Java API Reference
description: Campi obbligatori degli elementi della carta
type: docs
weight: 10
url: /it/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Elementi obbligatori (campi) della carta
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. |
| [getAddressState()](#getAddressState--) | DAJ, Parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Paese in cui è rilasciato il DL/ID. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Data di emissione del documento, MMDDCCYY per U.S., CCYYMMDD per Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Il numero deve identificare univocamente un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi in passato. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, Colore degli occhi del titolare della carta. |
| [getFamilyName()](#getFamilyName--) | DCS, Cognome del titolare della carta, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Nome del titolare della carta, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Altezza del titolare della carta. |
| [getMiddleName()](#getMiddleName--) | DAD, Secondo(i) nome(i) del titolare della carta. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Sesso del titolare della carta. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Codice di classe / gruppo veicolo specifico della giurisdizione, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Paese in cui è rilasciato il DL/ID. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Data di emissione del documento, MMDDCCYY per U.S., CCYYMMDD per Canada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Il numero deve identificare univocamente un documento specifico emesso a quel cliente rispetto ad altri che potrebbero essere stati emessi in passato. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Colore degli occhi del titolare della carta. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Cognome del titolare della carta, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Nome del titolare della carta, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Altezza del titolare della carta. |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Secondo(i) nome(i) del titolare della carta. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Sesso del titolare della carta. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Codice di classe / gruppo veicolo specifico della giurisdizione, DL, V6ANS |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. Se la parte finale del codice postale negli Stati Uniti non è nota, verranno utilizzati zeri per riempire la sequenza finale di numeri fino a 9 cifre, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS

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


DCG, Paese in cui viene rilasciato DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Data di emissione del documento, MMDDCCYY per U.S., CCYYMMDD per Canada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Il numero deve identificare in modo univoco un documento specifico rilasciato a quel cliente rispetto ad altri che potrebbero essere stati rilasciati in passato. Questo numero può servire a molteplici scopi di discriminazione del documento, numero di informazioni di audit e/o controllo dell'inventario, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Cognome del titolare della carta, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Nome del titolare della carta, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da " in" es. 6'1'' = "073 in" Centimetri (cm): numero di centimetri seguito da " cm" es. 181 centimetri="181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola ",". , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Codice di classe / gruppo veicolo specifico della giurisdizione, DL, V6ANS

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


DAI, Parte della città dell'indirizzo del titolare della carta, DL/ID, V20ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Parte del codice postale dell'indirizzo del titolare della carta negli Stati Uniti e Canada. Se la parte finale del codice postale negli Stati Uniti non è nota, verranno utilizzati zeri per riempire la sequenza finale di numeri fino a 9 cifre, DL/ID, F11ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Parte dello stato dell'indirizzo del titolare della carta, DL/ID, F2A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Parte della via dell'indirizzo del titolare della carta, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Paese in cui viene rilasciato DL/ID. U.S. = USA, Canada = CAN, DL/ID, F3A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Il numero assegnato o calcolato dall'autorità emittente, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Data di emissione del documento, MMDDCCYY per U.S., CCYYMMDD per Canada, DL/ID, F8N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Il numero deve identificare in modo univoco un documento specifico rilasciato a quel cliente rispetto ad altri che potrebbero essere stati rilasciati in passato. Questo numero può servire a molteplici scopi di discriminazione del documento, numero di informazioni di audit e/o controllo dell'inventario, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Codici di endorsement specifici della giurisdizione, DL, V5ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Colore degli occhi del titolare della carta. (codici ANSI D-20). DL/ID, F3A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Cognome del titolare della carta, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Nome del titolare della carta, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Altezza del titolare della carta. Pollici (in): numero di pollici seguito da " in" es. 6'1'' = "073 in" Centimetri (cm): numero di centimetri seguito da " cm" es. 181 centimetri="181 cm" , DL/ID, F6ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Secondo(i) nome(i) del titolare della carta. Nel caso di più secondi nomi devono essere separati da una virgola ",". , DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Un codice che indica se un campo è stato troncato (T), non è stato troncato (N) o se è sconosciuto se troncato (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Codici di restrizioni specifici della giurisdizione, DL, V12ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Sesso del titolare della carta. 1 = maschio, 2 = femmina, 9 = non specificato, DL/ID, F1N

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Codice di classe / gruppo veicolo specifico della giurisdizione, DL, V6ANS

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


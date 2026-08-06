---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode for Android via Java API-referentie
description: Klasse voor het opslaan van secundaire en aanvullende HIBC LIC-gegevens.
type: docs
weight: 35
url: /nl/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Klasse voor het opslaan van secundaire en aanvullende HIBC LIC-gegevens.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  SecondaryAndAdditionalData  waarde. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identificeert productiedatum. |
| [getExpiryDate()](#getExpiryDate--) | Identificeert vervaldatum. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identificeert het formaat van de vervaldatum. |
| [getLotNumber()](#getLotNumber--) | Identificeert lot- of batchnummer. |
| [getQuantity()](#getQuantity--) | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. |
| [getSerialNumber()](#getSerialNumber--) | Identificeert serienummer. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Instantieert secundaire en aanvullende aanvullende gegevens volgens het tekenreeksformaat van de HIBC LIC-specificatie. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identificeert productiedatum. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identificeert vervaldatum. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identificeert het formaat van de vervaldatum. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identificeert lot- of batchnummer. |
| [setQuantity(int value)](#setQuantity-int-) | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identificeert serienummer. |
| [toString()](#toString--) | Converteert gegevens naar tekenreeksformaat volgens de HIBC LIC-specificatie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  SecondaryAndAdditionalData  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een  SecondaryAndAdditionalData  waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Identificeert productiedatum. Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken. Standaardwaarde: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet is ingesteld op None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identificeert het formaat van de vervaldatum.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identificeert lot- of batchnummer. Lot/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identificeert serienummer. Serienummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Instantieert secundaire en aanvullende aanvullende gegevens volgens het tekenreeksformaat van de HIBC LIC-specificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Geformatteerde tekenreeks. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identificeert productiedatum. Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken. Standaardwaarde: DateTime.MinValue

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet is ingesteld op None.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identificeert het formaat van de vervaldatum.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identificeert lot- of batchnummer. Lot/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens. .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identificeert serienummer. Serienummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Converteert gegevens naar tekenreeksformaat volgens de HIBC LIC-specificatie.

**Returns:**
java.lang.String - Geformatteerde tekenreeks.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


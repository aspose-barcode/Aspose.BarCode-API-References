---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för lagring av HIBC LIC‑sekundär och ytterligare data.
type: docs
weight: 35
url: /sv/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Klass för lagring av HIBC LIC‑sekundär och ytterligare data.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  SecondaryAndAdditionalData  värde. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Identifierar tillverkningsdatum. |
| [getExpiryDate()](#getExpiryDate--) | Identifierar utgångsdatum. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Identifierar format för utgångsdatum. |
| [getLotNumber()](#getLotNumber--) | Identifierar parti- eller batchnummer. |
| [getQuantity()](#getQuantity--) | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. |
| [getSerialNumber()](#getSerialNumber--) | Identifierar serienummer. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Instansierar sekundära och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Identifierar tillverkningsdatum. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Identifierar utgångsdatum. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Identifierar format för utgångsdatum. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Identifierar parti- eller batchnummer. |
| [setQuantity(int value)](#setQuantity-int-) | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Identifierar serienummer. |
| [toString()](#toString--) | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |
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


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  SecondaryAndAdditionalData  värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  SecondaryAndAdditionalData  värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
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


Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Identifierar utgångsdatum. Kommer att användas om ExpiryDateFormat inte är satt till None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Identifierar format för utgångsdatum.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Identifierar parti- eller batchnummer. Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken i längd. .

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken i längd.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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


Instansierar sekundära och ytterligare kompletterande data från strängformat enligt HIBC LIC-specifikationen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Formaterad sträng. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Identifierar utgångsdatum. Kommer att användas om ExpiryDateFormat inte är satt till None.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Identifierar format för utgångsdatum.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Identifierar parti- eller batchnummer. Parti-/batchnummer måste vara en alfanumerisk sträng med upp till 18 tecken i längd. .

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken i längd.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Konverterar data till strängformat enligt HIBC LIC-specifikationen.

**Returns:**
java.lang.String - Formaterad sträng.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


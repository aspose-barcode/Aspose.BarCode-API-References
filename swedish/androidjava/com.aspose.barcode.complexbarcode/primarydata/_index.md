---
title: PrimaryData
second_title: Aspose.BarCode for Android via Java API-referens
description: Klass för lagring av HIBC LIC‑primärdata.
type: docs
weight: 34
url: /sv/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Klass för lagring av HIBC LIC‑primärdata.
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  PrimaryData  värde. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifierar datum för etikettörens identifieringskod. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifierar produkt- eller katalognummer. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifierar enhetsmått-ID. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Instansierar primärdata från strängformat enligt HIBC LIC-specifikationen. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifierar datum för etikettörens identifieringskod. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifierar produkt- eller katalognummer. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifierar enhetsmått-ID. |
| [toString()](#toString--) | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat  PrimaryData  värde.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett  PrimaryData  värde att jämföra med detta objekt. |

**Returns:**
boolean -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, där det första tecknet alltid är alfabetiskt.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identifierar enhetsmått-ID. Enhetsmått-ID måste vara ett heltal mellan 0 och 9.

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Instansierar primärdata från strängformat enligt HIBC LIC-specifikationen.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Formaterad sträng. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identifierar datum för etikettörens identifieringskod. Etikettörens identifieringskod måste vara en alfanumerisk sträng på 4 tecken, där det första tecknet alltid är alfabetiskt.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identifierar produkt- eller katalognummer. Produkt- eller katalognummer måste vara en alfanumerisk sträng med upp till 18 tecken.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identifierar enhetsmått-ID. Enhetsmått-ID måste vara ett heltal mellan 0 och 9.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

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


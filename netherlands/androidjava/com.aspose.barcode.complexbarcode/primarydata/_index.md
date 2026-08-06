---
title: PrimaryData
second_title: Aspose.BarCode for Android via Java API-referentie
description: Klasse voor het opslaan van primaire HIBC LIC-gegevens.
type: docs
weight: 34
url: /nl/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Klasse voor het opslaan van primaire HIBC LIC-gegevens.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  PrimaryData  waarde. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identificeert datum van labeleridentificatiecode. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identificeert product- of catalogusnummer. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identificeert eenheid‑van‑maat‑ID. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Instantieert primary data vanuit tekenreeksformaat volgens de HIBC LIC-specificatie. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identificeert datum van labeleridentificatiecode. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identificeert product- of catalogusnummer. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identificeert eenheid‑van‑maat‑ID. |
| [toString()](#toString--) | Converteert gegevens naar tekenreeksformaat volgens de HIBC LIC-specificatie. |
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


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde  PrimaryData  waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een  PrimaryData  waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
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


Identificeert datum van labeler‑identificatiecode. Labeler‑identificatiecode moet een alfanumerieke tekenreeks van 4 symbolen zijn, waarbij het eerste teken altijd een letter is.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identificeert product- of catalogusnummer. Product- of catalogusnummer moet een alfanumerieke tekenreeks van maximaal 18 symbolen zijn.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identificeert eenheid‑van‑maat‑ID. Eenheid‑van‑maat‑ID moet een geheel getal tussen 0 en 9 zijn.

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Instantieert primary data vanuit tekenreeksformaat volgens de HIBC LIC-specificatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Geformatteerde tekenreeks. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identificeert datum van labeler‑identificatiecode. Labeler‑identificatiecode moet een alfanumerieke tekenreeks van 4 symbolen zijn, waarbij het eerste teken altijd een letter is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identificeert product- of catalogusnummer. Product- of catalogusnummer moet een alfanumerieke tekenreeks van maximaal 18 symbolen zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identificeert eenheid‑van‑maat‑ID. Eenheid‑van‑maat‑ID moet een geheel getal tussen 0 en 9 zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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


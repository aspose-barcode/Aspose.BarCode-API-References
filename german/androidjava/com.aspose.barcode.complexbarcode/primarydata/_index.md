---
title: PrimaryData
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Klasse zum Speichern primärer HIBC LIC‑Daten.
type: docs
weight: 34
url: /de/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Klasse zum Speichern primärer HIBC LIC‑Daten.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  PrimaryData  Wert entspricht. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Identifiziert das Datum des Kennzeichencodes des Etikettierers. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Identifiziert Produkt- oder Katalognummer. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Identifiziert die ID der Maßeinheit. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Instanziiert Primärdaten aus dem Zeichenkettenformat gemäß HIBC LIC-Spezifikation. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Identifiziert das Datum des Kennzeichencodes des Etikettierers. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Identifiziert Produkt- oder Katalognummer. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Identifiziert die ID der Maßeinheit. |
| [toString()](#toString--) | Konvertiert Daten in das Zeichenkettenformat gemäß HIBC LIC Spezifikation. |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen  PrimaryData  Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein PrimaryData-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
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


Identifiziert das Datum des Kennzeichencodes des Etikettierers. Der Kennzeichencode des Etikettierers muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch sein muss.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Identifiziert die ID der Maßeinheit. Die ID der Maßeinheit muss ein ganzzahliger Wert von 0 bis 9 sein.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Instanziiert Primärdaten aus dem Zeichenkettenformat gemäß HIBC LIC-Spezifikation.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Formatierte Zeichenkette. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Identifiziert das Datum des Kennzeichencodes des Etikettierers. Der Kennzeichencode des Etikettierers muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch sein muss.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Identifiziert Produkt- oder Katalognummer. Produkt- oder Katalognummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Identifiziert die ID der Maßeinheit. Die ID der Maßeinheit muss ein ganzzahliger Wert von 0 bis 9 sein.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### toString() {#toString--}
```
public String toString()
```


Konvertiert Daten in das Zeichenkettenformat gemäß HIBC LIC Spezifikation.

**Returns:**
java.lang.String - Formatierte Zeichenkette.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


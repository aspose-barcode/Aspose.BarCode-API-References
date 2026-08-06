---
title: ExtCodetextBuilder
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Hilfsklasse zur automatischen Codetext-Generierung des erweiterten Codetext-Modus
type: docs
weight: 40
url: /de/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Hilfsklasse zur automatischen Codetext-Generierung des erweiterten Codetext-Modus
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [clear()](#clear--) | Löscht erweiterte Codetext-Elemente |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Erzeugt erweiterten Codetext aus der Liste der Generierungselemente. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Prüft, ob das vorherige Element durch "\\000000" geschützt werden muss |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Fügt Codetext mit erweitertem Kanalbezeichner hinzu.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| ECIEncoding | int | Erweiterter Kanalbezeichner |
| codetext | java.lang.String | Codetext in Unicode, der als erweitertes Codetext-Element mit erweitertem Kanalbezeichner hinzugefügt wird |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in Unicode, der als erweitertes Codetext-Element hinzugefügt wird |

### clear() {#clear--}
```
public void clear()
```


Löscht erweiterte Codetext-Elemente

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


Erzeugt erweiterten Codetext aus der Liste der Generierungselemente.

**Returns:**
java.lang.String - Gibt den String des erweiterten Codetextes zurück.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


Prüft, ob das vorherige Element durch "\\000000" geschützt werden muss

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean – Notwendigkeit zum Schützen
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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


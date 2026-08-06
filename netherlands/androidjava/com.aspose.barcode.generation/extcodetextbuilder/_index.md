---
title: ExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API-referentie
description: Helperklasse voor automatische codetekstgeneratie van de Extended Codetext-modus
type: docs
weight: 40
url: /nl/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Helperklasse voor automatische codetekstgeneratie van de Extended Codetext-modus
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Voegt codetext toe met Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Voegt platte codetekst toe aan de uitgebreide codetekstitems |
| [clear()](#clear--) | Leegt uitgebreide codetekstitems |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genereer uitgebreide codetekst vanuit de lijst met generatie‑items. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Controleert de noodzaak om het vorige item te beschermen met "\\000000" |
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


Voegt codetext toe met Extended Channel Identifier

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ECIEncoding | int | Uitgebreide kanaalidentificatie |
| codetekst | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem met Uitgebreide kanaalidentificatie |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Voegt platte codetekst toe aan de uitgebreide codetekstitems

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| codetekst | java.lang.String | Codetekst in Unicode om toe te voegen als uitgebreid codetekstitem |

### clear() {#clear--}
```
public void clear()
```


Leegt uitgebreide codetekstitems

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Genereer uitgebreide codetekst vanuit de lijst met generatie‑items.

**Returns:**
java.lang.String - Retourneer string van uitgebreide codetekst.
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


Controleert de noodzaak om het vorige item te beschermen met "\\000000"

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean - Noodzaak om te beschermen
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


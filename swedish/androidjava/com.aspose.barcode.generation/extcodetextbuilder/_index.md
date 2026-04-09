---
title: ExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API-referens
description: Hjälparklass för automatisk kodtextgenerering i Utökad kodtextläge
type: docs
weight: 40
url: /sv/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

Hjälparklass för automatisk kodtextgenerering i Utökad kodtextläge
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Lägger till kodtext med utökad kanalidentifierare |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Adds plain codetext to the extended codetext items |
| [clear()](#clear--) | Clears extended codetext items |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Generera utökad kodtext från listan med genereringsobjekt. |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | Checks necessity to shield previous item by "\\000000" |
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


Lägger till kodtext med utökad kanalidentifierare

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item with Extended Channel Identifier |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


Adds plain codetext to the extended codetext items

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode to add as extended codetext item |

### clear() {#clear--}
```
public void clear()
```


Clears extended codetext items

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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


Generera utökad kodtext från listan med genereringsobjekt.

**Returns:**
java.lang.String - Returnera sträng med utökad kodtext.
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


Checks necessity to shield previous item by "\\000000"

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| Index | int | Index in m\_List |

**Returns:**
boolean - Necessity to shield
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


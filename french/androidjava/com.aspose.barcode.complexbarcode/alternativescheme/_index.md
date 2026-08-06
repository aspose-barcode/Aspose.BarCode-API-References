---
title: AlternativeScheme
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Instructions du schéma de paiement alternatif
type: docs
weight: 11
url: /fr/androidjava/com.aspose.barcode.complexbarcode/alternativescheme/
---
**Inheritance:**
java.lang.Object
```
public final class AlternativeScheme
```

Instructions du schéma de paiement alternatif
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AlternativeScheme()](#AlternativeScheme--) |  |
| [AlternativeScheme(String instruction)](#AlternativeScheme-java.lang.String-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| [getClass()](#getClass--) |  |
| [getInstruction()](#getInstruction--) | Gets the payment instruction for a given bill. |
| [hashCode()](#hashCode--) | Gets the hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setInstruction(String value)](#setInstruction-java.lang.String-) | Gets the payment instruction for a given bill. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AlternativeScheme() {#AlternativeScheme--}
```
public AlternativeScheme()
```


### AlternativeScheme(String instruction) {#AlternativeScheme-java.lang.String-}
```
public AlternativeScheme(String instruction)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'objet spécifié est égal à l'objet actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current object. |

**Returns:**
boolean -  true  if the specified object is equal to the current object; otherwise,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstruction() {#getInstruction--}
```
public String getInstruction()
```


Gets the payment instruction for a given bill.

The instruction consists of a two letter abbreviation for the scheme, a separator characters and a sequence of parameters(separated by the character at index 2).

Value: The payment instruction.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gets the hash code for this instance.

**Returns:**
int - A hash code for the current object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setInstruction(String value) {#setInstruction-java.lang.String-}
```
public void setInstruction(String value)
```


Gets the payment instruction for a given bill.

The instruction consists of a two letter abbreviation for the scheme, a separator characters and a sequence of parameters(separated by the character at index 2).

Value: The payment instruction.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


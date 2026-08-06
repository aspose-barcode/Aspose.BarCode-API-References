---
title: AutoSizeMode
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης.
type: docs
weight: 72
url: /el/androidjava/com.aspose.barcode.generation/autosizemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AutoSizeMode extends Enum<AutoSizeMode>
```

Καθορίζει τους διαφορετικούς τύπους αυτόματων λειτουργιών μεγέθυνσης.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [INTERPOLATION](#INTERPOLATION) | Αλλάζει το μέγεθος του barcode στο καθορισμένο μέγεθος. |
| [NEAREST](#NEAREST) | Αλλάζει το μέγεθος του barcode στο πλησιέστερο χαμηλότερο δυνατό μέγεθος που καθορίζεται από τις ιδιότητες ImageWidth και ImageHeight. |
| [NONE](#NONE) | Η αυτόματη αλλαγή μεγέθους είναι απενεργοποιημένη. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### INTERPOLATION {#INTERPOLATION}
```
public static final AutoSizeMode INTERPOLATION
```


Αλλάζει το μέγεθος του barcode στο καθορισμένο μέγεθος. Το μέγεθος μπορεί να καθοριστεί από τις ιδιότητες ImageWidth και ImageHeight. Το παραγόμενο barcode μπορεί να είναι μη έγκυρο (μη αναγνώσιμο) μετά την κλιμάκωση.

### NEAREST {#NEAREST}
```
public static final AutoSizeMode NEAREST
```


Αλλάζει το μέγεθος του barcode στο πλησιέστερο χαμηλότερο δυνατό μέγεθος που καθορίζεται από τις ιδιότητες ImageWidth και ImageHeight. Διατηρεί την προεπιλεγμένη αναλογία διαστάσεων.

### NONE {#NONE}
```
public static final AutoSizeMode NONE
```


Η αυτόματη αλλαγή μεγέθους είναι απενεργοποιημένη.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static AutoSizeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### values() {#values--}
```
public static AutoSizeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AutoSizeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


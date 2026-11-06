---
title: "GraphicsUnit"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Καθορίζει τη μονάδα μέτρησης για τα δεδομένα που δόθηκαν."
type: docs
weight: 87
url: /el/androidjava/com.aspose.barcode.generation/graphicsunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum GraphicsUnit extends Enum<GraphicsUnit>
```

Καθορίζει τη μονάδα μέτρησης για τα δεδομένα που δόθηκαν.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DISPLAY](#DISPLAY) | Καθορίζει τη μονάδα μέτρησης της συσκευής εμφάνισης. |
| [DOCUMENT](#DOCUMENT) | Καθορίζει τη μονάδα εγγράφου (1/300 ίντσα) ως μονάδα μέτρησης. |
| [INCH](#INCH) | Καθορίζει το ίντσα ως μονάδα μέτρησης. |
| [MILLIMETER](#MILLIMETER) | Καθορίζει το χιλιοστόμετρο ως μονάδα μέτρησης. |
| [PIXEL](#PIXEL) | Καθορίζει ένα pixel συσκευής ως μονάδα μέτρησης. |
| [POINT](#POINT) | Καθορίζει το σημείο εκτυπωτή (1/72 ίντσα) ως μονάδα μέτρησης. |
| [WORLD](#WORLD) | Καθορίζει τη μονάδα του παγκόσμιου συστήματος συντεταγμένων ως μονάδα μέτρησης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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
### DISPLAY {#DISPLAY}
```
public static final GraphicsUnit DISPLAY
```


Καθορίζει τη μονάδα μέτρησης της συσκευής εμφάνισης. Συνήθως pixels για οθόνες βίντεο και 1/100 ίντσα για εκτυπωτές.

### DOCUMENT {#DOCUMENT}
```
public static final GraphicsUnit DOCUMENT
```


Καθορίζει τη μονάδα εγγράφου (1/300 ίντσα) ως μονάδα μέτρησης.

### INCH {#INCH}
```
public static final GraphicsUnit INCH
```


Καθορίζει το ίντσα ως μονάδα μέτρησης.

### MILLIMETER {#MILLIMETER}
```
public static final GraphicsUnit MILLIMETER
```


Καθορίζει το χιλιοστόμετρο ως μονάδα μέτρησης.

### PIXEL {#PIXEL}
```
public static final GraphicsUnit PIXEL
```


Καθορίζει ένα pixel συσκευής ως μονάδα μέτρησης.

### POINT {#POINT}
```
public static final GraphicsUnit POINT
```


Καθορίζει το σημείο εκτυπωτή (1/72 ίντσα) ως μονάδα μέτρησης.

### WORLD {#WORLD}
```
public static final GraphicsUnit WORLD
```


Καθορίζει τη μονάδα του παγκόσμιου συστήματος συντεταγμένων ως μονάδα μέτρησης.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static GraphicsUnit fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
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
public static GraphicsUnit valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit)
### values() {#values--}
```
public static GraphicsUnit[] values()
```




**Returns:**
com.aspose.barcode.generation.GraphicsUnit[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


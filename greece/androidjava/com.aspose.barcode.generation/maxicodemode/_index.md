---
title: "MaxiCodeMode"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Περιέχει λειτουργίες κωδικοποίησης MaxiCode."
type: docs
weight: 95
url: /el/androidjava/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

Περιέχει λειτουργίες κωδικοποίησης MaxiCode.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MODE_2](#MODE-2) | Η λειτουργία 2 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. |
| [MODE_3](#MODE-3) | Η λειτουργία 3 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. |
| [MODE_4](#MODE-4) | Η λειτουργία 4 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με σύντομη διόρθωση ECC. |
| [MODE_5](#MODE-5) | Η λειτουργία 5 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με μακρά διόρθωση ECC. |
| [MODE_6](#MODE-6) | Η λειτουργία 6 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με σύντομη διόρθωση ECC. |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


Mode 2 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Έχει έναν 9-ψήφιο ταχυδρομικό κώδικα και χρησιμοποιείται μόνο στις ΗΠΑ.

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


Mode 3 κωδικοποιεί τις ταχυδρομικές πληροφορίες στο πρώτο μήνυμα και τα δεδομένα στο δεύτερο μήνυμα. Έχει έναν 6-χαρακτήρων αλφαριθμητικό ταχυδρομικό κώδικα και χρησιμοποιείται παγκοσμίως.

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


Η λειτουργία 4 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με σύντομη διόρθωση ECC.

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


Η λειτουργία 5 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με μακρά διόρθωση ECC.

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


Mode 6 κωδικοποιεί δεδομένα στο πρώτο και δεύτερο μήνυμα με σύντομη διόρθωση ECC. Χρησιμοποιείται για την κωδικοποίηση συσκευών.

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
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
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


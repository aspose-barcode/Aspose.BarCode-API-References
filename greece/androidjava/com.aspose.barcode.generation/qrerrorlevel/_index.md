---
title: "QRErrorLevel"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon."
type: docs
weight: 104
url: /el/androidjava/com.aspose.barcode.generation/qrerrorlevel/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QRErrorLevel extends Enum<QRErrorLevel>
```

Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon. Από χαμηλό προς υψηλό: LEVEL\_L, LEVEL\_M, LEVEL\_Q, LEVEL\_H.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [LEVEL_H](#LEVEL-H) | Το επίπεδο διόρθωσης σφαλμάτων H μπορεί να εφαρμοστεί σε barcode QR και RectMicroQR. |
| [LEVEL_L](#LEVEL-L) | Το επίπεδο διόρθωσης σφαλμάτων L μπορεί να εφαρμοστεί σε barcode QR και MicroQR. |
| [LEVEL_M](#LEVEL-M) | Το επίπεδο διόρθωσης σφαλμάτων M μπορεί να εφαρμοστεί σε barcode QR, RectMicroQR και MicroQR με εκδόσεις από M2 έως M4. |
| [LEVEL_Q](#LEVEL-Q) | Το επίπεδο διόρθωσης σφαλμάτων Q μπορεί να εφαρμοστεί σε barcode QR και MicroQR με έκδοση M4. |
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
### LEVEL_H {#LEVEL-H}
```
public static final QRErrorLevel LEVEL_H
```


Το επίπεδο διόρθωσης σφαλμάτων H μπορεί να εφαρμοστεί σε barcode QR και RectMicroQR. Επιτρέπει την ανάκτηση του 30% του κώδικα κειμένου.

### LEVEL_L {#LEVEL-L}
```
public static final QRErrorLevel LEVEL_L
```


Το επίπεδο διόρθωσης σφαλμάτων L μπορεί να εφαρμοστεί σε barcode QR και MicroQR. Επιτρέπει την ανάκτηση του 7% του κώδικα κειμένου.

### LEVEL_M {#LEVEL-M}
```
public static final QRErrorLevel LEVEL_M
```


Το επίπεδο διόρθωσης σφαλμάτων M μπορεί να εφαρμοστεί σε barcode QR, RectMicroQR και MicroQR με εκδόσεις από M2 έως M4. Επιτρέπει την ανάκτηση του 15% του κώδικα κειμένου.

### LEVEL_Q {#LEVEL-Q}
```
public static final QRErrorLevel LEVEL_Q
```


Το επίπεδο διόρθωσης σφαλμάτων Q μπορεί να εφαρμοστεί σε barcode QR και MicroQR με έκδοση M4. Επιτρέπει την ανάκτηση του 25% του κώδικα κειμένου.

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
public static QRErrorLevel fromValue(int value)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
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
public static QRErrorLevel valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### values() {#values--}
```
public static QRErrorLevel[] values()
```




**Returns:**
com.aspose.barcode.generation.QRErrorLevel[]
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


---
title: "CMYKColor"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Κλάση για χρώμα CMYK."
type: docs
weight: 19
url: /el/androidjava/com.aspose.barcode.generation/cmykcolor/
---
**Inheritance:**
java.lang.Object
```
public class CMYKColor
```

Κλάση για χρώμα CMYK. Το Null σημαίνει ότι το CMYK δεν χρησιμοποιείται, το προεπιλεγμένο χρώμα RGB είναι σε χρήση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CMYKColor(int c, int m, int y, int k)](#CMYKColor-int-int-int-int-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CMYKColor  από τιμές CMYK. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [C](#C) |  |
| [K](#K) |  |
| [M](#M) |  |
| [Y](#Y) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Συγκρίνει αν οι τιμές των χρωμάτων είναι ίδιες |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Κώδικας κατακερματισμού του CMYKColor |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CMYKColor(int c, int m, int y, int k) {#CMYKColor-int-int-int-int-}
```
public CMYKColor(int c, int m, int y, int k)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  CMYKColor  από τιμές CMYK. Οι τιμές CMYK είναι 0-100.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| c | int | Τιμή κυανίου [0, 100] |
| m | int | Τιμή ματζέντας [0, 100] |
| y | int | Τιμή κίτρινου [0, 100] |
| k | int | Τιμή μαύρου [0, 100] |

### C {#C}
```
public float C
```


### K {#K}
```
public float K
```


### M {#M}
```
public float M
```


### Y {#Y}
```
public float Y
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Συγκρίνει αν οι τιμές των χρωμάτων είναι ίδιες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | CMYKColor για σύγκριση |

**Returns:**
boolean - Είναι οι τιμές ίδιες
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Κώδικας κατακερματισμού του CMYKColor

**Returns:**
int - Κώδικας κατακερματισμού του CMYKColor
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


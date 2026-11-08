---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Οι ιδιότητες υποαρχείου USA DL, η μετατόπιση και το μήκος, ορίζονται αυτόματα."
type: docs
weight: 12
url: /el/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Οι ιδιότητες, η μετατόπιση και το μήκος του υποαρχείου USA DL ορίζονται αυτόματα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 Αυτά τα byte περιέχουν μια 4-ψήφια αριθμητική τιμή που καθορίζει το μήκος του υποαρχείου σε byte. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του υποαρχείου. Ένας τερματιστής τμήματος = 1. |
| [getOffset()](#getOffset--) | 4-ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των byte από την αρχή του αρχείου μέχρι τη θέση όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο υποαρχείο. Το πρώτο byte του αρχείου βρίσκεται στη μετατόπιση 0. |
| [getType()](#getType--) | 2-byte τύπος του υποαρχείου, όπως "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Αυτά τα byte περιέχουν μια 4-ψήφια αριθμητική τιμή που καθορίζει το μήκος του υποαρχείου σε byte. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του υποαρχείου. Ένας τερματιστής τμήματος = 1. |
| [setOffset(int value)](#setOffset-int-) | 4-ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των byte από την αρχή του αρχείου μέχρι τη θέση όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο υποαρχείο. Το πρώτο byte του αρχείου βρίσκεται στη μετατόπιση 0. |
| [setType(String value)](#setType-java.lang.String-) | 2-byte τύπος του υποαρχείου, όπως "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 Αυτά τα byte περιέχουν μια 4-ψήφια αριθμητική τιμή που καθορίζει το μήκος του υποαρχείου σε byte. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του υποαρχείου. Ένας τερματιστής τμήματος = 1. Κάθε υποαρχείο πρέπει να αρχίζει με τον δύο-χαρακτήρα Subfile Type και αυτοί οι δύο χαρακτήρες πρέπει επίσης να συμπεριλαμβάνονται στο μήκος.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4-ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των byte από την αρχή του αρχείου μέχρι τη θέση όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο υποαρχείο. Το πρώτο byte του αρχείου βρίσκεται στη μετατόπιση 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


2-byte τύπος του υποαρχείου, όπως "DL"

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 Αυτά τα byte περιέχουν μια 4-ψήφια αριθμητική τιμή που καθορίζει το μήκος του υποαρχείου σε byte. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του υποαρχείου. Ένας τερματιστής τμήματος = 1. Κάθε υποαρχείο πρέπει να αρχίζει με τον δύο-χαρακτήρα Subfile Type και αυτοί οι δύο χαρακτήρες πρέπει επίσης να συμπεριλαμβάνονται στο μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4-ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των byte από την αρχή του αρχείου μέχρι τη θέση όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο υποαρχείο. Το πρώτο byte του αρχείου βρίσκεται στη μετατόπιση 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


2-byte τύπος του υποαρχείου, όπως "DL"

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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
public final native void wait(long arg0)
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


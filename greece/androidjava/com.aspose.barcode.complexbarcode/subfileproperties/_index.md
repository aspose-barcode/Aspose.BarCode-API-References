---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Οι ιδιότητες offset και μήκος του υποαρχείου USA DL ορίζονται αυτόματα."
type: docs
weight: 12
url: /el/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

Οι ιδιότητες υποαρχείου USA DL, η μετατόπιση και το μήκος ορίζονται αυτόματα.
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
| [getLength()](#getLength--) | 4 Αυτά τα bytes περιέχουν μια 4ψήφια αριθμητική τιμή που καθορίζει το μήκος του Subfile σε bytes. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του subfile. Ένας τερματιστής τμήματος = 1. |
| [getOffset()](#getOffset--) | 4 ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των bytes από την αρχή του αρχείου έως το σημείο όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο sub-file. Το πρώτο byte στο αρχείο βρίσκεται στο offset 0. |
| [getType()](#getType--) | Τύπος subfile 2 byte, όπως "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 Αυτά τα bytes περιέχουν μια 4ψήφια αριθμητική τιμή που καθορίζει το μήκος του Subfile σε bytes. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του subfile. Ένας τερματιστής τμήματος = 1. |
| [setOffset(int value)](#setOffset-int-) | 4 ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των bytes από την αρχή του αρχείου έως το σημείο όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο sub-file. Το πρώτο byte στο αρχείο βρίσκεται στο offset 0. |
| [setType(String value)](#setType-java.lang.String-) | Τύπος subfile 2 byte, όπως "DL" |
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


4 Αυτά τα bytes περιέχουν μια 4ψήφια αριθμητική τιμή που καθορίζει το μήκος του Subfile σε bytes. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του subfile. Ένας τερματιστής τμήματος = 1. Κάθε subfile πρέπει να αρχίζει με τον δύο-χαρακτήρων Subfile Type και αυτοί οι δύο χαρακτήρες πρέπει επίσης να συμπεριλαμβάνονται στο μήκος.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4 ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των bytes από την αρχή του αρχείου έως το σημείο όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο sub-file. Το πρώτο byte στο αρχείο βρίσκεται στο offset 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


Τύπος subfile 2 byte, όπως "DL"

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


4 Αυτά τα bytes περιέχουν μια 4ψήφια αριθμητική τιμή που καθορίζει το μήκος του Subfile σε bytes. Ο τερματιστής τμήματος πρέπει να συμπεριλαμβάνεται στον υπολογισμό του μήκους του subfile. Ένας τερματιστής τμήματος = 1. Κάθε subfile πρέπει να αρχίζει με τον δύο-χαρακτήρων Subfile Type και αυτοί οι δύο χαρακτήρες πρέπει επίσης να συμπεριλαμβάνονται στο μήκος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4 ψήφια αριθμητική τιμή που καθορίζει τον αριθμό των bytes από την αρχή του αρχείου έως το σημείο όπου βρίσκονται τα δεδομένα που σχετίζονται με το συγκεκριμένο sub-file. Το πρώτο byte στο αρχείο βρίσκεται στο offset 0.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


Τύπος subfile 2 byte, όπως "DL"

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


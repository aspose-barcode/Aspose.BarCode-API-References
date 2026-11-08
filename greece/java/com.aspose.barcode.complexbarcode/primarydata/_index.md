---
title: "PrimaryData"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Κλάση για αποθήκευση των πρωτεύοντων δεδομένων HIBC LIC."
type: docs
weight: 33
url: /el/java/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Κλάση για αποθήκευση των πρωτεύοντων δεδομένων HIBC LIC.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  PrimaryData . |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Αναγνωρίζει ημερομηνία κωδικού ταυτοποίησης ετικετοποιητή. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Αναγνωρίζει αριθμό προϊόντος ή καταλόγου. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Αναγνωρίζει ταυτότητα μονάδας μέτρησης. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Δημιουργεί πρωτεύοντα δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Αναγνωρίζει ημερομηνία κωδικού ταυτοποίησης ετικετοποιητή. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Αναγνωρίζει αριθμό προϊόντος ή καταλόγου. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Αναγνωρίζει ταυτότητα μονάδας μέτρησης. |
| [toString()](#toString--) | Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  PrimaryData .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή  PrimaryData  για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα να είναι αλφαβητικός.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικό μέχρι 18 σύμβολα.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


Δημιουργεί πρωτεύοντα δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Μορφοποιημένη συμβολοσειρά. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητικό 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα να είναι αλφαβητικός.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητικό μέχρι 18 σύμβολα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

**Returns:**
java.lang.String - Μορφοποιημένη συμβολοσειρά.
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


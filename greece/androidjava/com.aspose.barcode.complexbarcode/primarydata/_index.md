---
title: PrimaryData
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για αποθήκευση των πρωτεύοντων δεδομένων HIBC LIC.
type: docs
weight: 34
url: /el/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

Κλάση για αποθήκευση των πρωτεύοντων δεδομένων HIBC LIC.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  PrimaryData . |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | Καθορίζει την ημερομηνία κωδικού ταυτοποίησης του ετικετοποιητή. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | Δημιουργεί μια παρουσία του πρωτεύοντος δεδομένου από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | Καθορίζει την ημερομηνία κωδικού ταυτοποίησης του ετικετοποιητή. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή PrimaryData για σύγκριση με αυτήν την παρουσία. |

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


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητική συμβολοσειρά 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 σύμβολα μήκος.

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
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
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


Δημιουργεί μια παρουσία του πρωτεύοντος δεδομένου από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | Μορφοποιημένη συμβολοσειρά. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


Αναγνωρίζει την ημερομηνία του κωδικού ταυτοποίησης του ετικετοποιητή. Ο κωδικός ταυτοποίησης του ετικετοποιητή πρέπει να είναι αλφαριθμητική συμβολοσειρά 4 συμβόλων, με τον πρώτο χαρακτήρα πάντα αλφαβητικό.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


Αναγνωρίζει τον αριθμό προϊόντος ή καταλόγου. Ο αριθμός προϊόντος ή καταλόγου πρέπει να είναι αλφαριθμητική συμβολοσειρά έως 18 σύμβολα μήκος.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


Αναγνωρίζει το αναγνωριστικό μονάδας μέτρησης. Το αναγνωριστικό μονάδας μέτρησης πρέπει να είναι ακέραια τιμή από 0 έως 9.

**Parameters:**
| Parameter | Type | Περιγραφή |
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


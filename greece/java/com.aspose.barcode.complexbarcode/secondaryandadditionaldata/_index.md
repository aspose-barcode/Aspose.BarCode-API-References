---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Κλάση για αποθήκευση των δευτερευόντων και πρόσθετων δεδομένων HIBC LIC."
type: docs
weight: 34
url: /el/java/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

Κλάση για αποθήκευση των δευτερευόντων και πρόσθετων δεδομένων HIBC LIC.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη  SecondaryAndAdditionalData  τιμή. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | Αναγνωρίζει ημερομηνία κατασκευής. |
| [getExpiryDate()](#getExpiryDate--) | Αναγνωρίζει ημερομηνία λήξης. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | Αναγνωρίζει μορφή ημερομηνίας λήξης. |
| [getLotNumber()](#getLotNumber--) | Αναγνωρίζει αριθμό παρτίδας ή δέσμης. |
| [getQuantity()](#getQuantity--) | Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. |
| [getSerialNumber()](#getSerialNumber--) | Αναγνωρίζει σειριακό αριθμό. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | Αναγνωρίζει ημερομηνία κατασκευής. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | Αναγνωρίζει ημερομηνία λήξης. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | Αναγνωρίζει μορφή ημερομηνίας λήξης. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | Αναγνωρίζει αριθμό παρτίδας ή δέσμης. |
| [setQuantity(int value)](#setQuantity-int-) | Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | Αναγνωρίζει σειριακό αριθμό. |
| [toString()](#toString--) | Μετατρέπει τα δεδομένα σε μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη  SecondaryAndAdditionalData  τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή  SecondaryAndAdditionalData  για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


Αναγνωρίζει ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


Αναγνωρίζει ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν είναι ορισμένο σε None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


Αναγνωρίζει μορφή ημερομηνίας λήξης.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


Αναγνωρίζει αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητική συμβολοσειρά με μέγιστο μήκος 18 συμβόλων.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


Αναγνωρίζει σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά με μέγιστο μήκος 18 συμβόλων.

**Returns:**
java.lang.String
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




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | Μορφοποιημένη συμβολοσειρά. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


Αναγνωρίζει ημερομηνία κατασκευής. Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: DateTime.MinValue

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


Αναγνωρίζει ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν είναι ορισμένο σε None.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


Αναγνωρίζει μορφή ημερομηνίας λήξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


Αναγνωρίζει αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητική συμβολοσειρά με μέγιστο μήκος 18 συμβόλων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


Αναγνωρίζει σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητική συμβολοσειρά με μέγιστο μήκος 18 συμβόλων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

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


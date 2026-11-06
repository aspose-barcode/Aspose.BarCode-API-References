---
title: "Διεύθυνση"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Διεύθυνση του πιστωτή ή του οφειλέτη."
type: docs
weight: 10
url: /el/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

Διεύθυνση του πιστωτή ή του οφειλέτη.

Μπορείτε είτε να ορίσετε τη οδό, τον αριθμό σπιτιού, τον ταχυδρομικό κώδικα και την πόλη (τύπος  *structured address* ) ή τη γραμμή διεύθυνσης 1 και 2 (τύπος  *combined address elements* ). Ο τύπος ορίζεται αυτόματα μόλις οριστεί οποιοδήποτε από αυτά τα πεδία. Πριν οριστούν τα πεδία, ο τύπος διεύθυνσης είναι  *undetermined* . Εάν τα πεδία και των δύο τύπων οριστούν, ο τύπος διεύθυνσης γίνεται  *conflicting* . Το όνομα και ο κωδικός χώρας πρέπει πάντα να ορίζονται εκτός εάν όλα τα πεδία είναι κενά.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Address()](#Address--) | Δημιουργεί ένα στιγμιότυπο του Address |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clear()](#clear--) | Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [getAddressLine1()](#getAddressLine1--) | Αποκτά το address line 1. |
| [getAddressLine2()](#getAddressLine2--) | Αποκτά το address line 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Λαμβάνει τον διψήφιο κωδικό χώρας ISO. |
| [getHouseNo()](#getHouseNo--) | Λαμβάνει τον αριθμό σπιτιού. |
| [getName()](#getName--) | Λαμβάνει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [getPostalCode()](#getPostalCode--) | Λαμβάνει τον ταχυδρομικό κώδικα. |
| [getStreet()](#getStreet--) | Λαμβάνει την οδό. |
| [getTown()](#getTown--) | Λαμβάνει την πόλη ή κωμόπολη. |
| [getType()](#getType--) | Λαμβάνει τον τύπο διεύθυνσης. |
| [hashCode()](#hashCode--) | Αποκτά τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Ορίζει τη γραμμή διεύθυνσης 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Ορίζει τη γραμμή διεύθυνσης 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Ορίζει τον διψήφιο κωδικό χώρας ISO. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Ορίζει τον αριθμό σπιτιού. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Ορίζει τον ταχυδρομικό κώδικα. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Ορίζει την οδό. |
| [setTown(String value)](#setTown-java.lang.String-) | Ορίζει την πόλη ή κωμόπολη. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Δημιουργεί ένα στιγμιότυπο του Address

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο. |

**Returns:**
boolean -  true  εάν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Αποκτά το address line 1.

Η γραμμή διεύθυνσης 1 περιέχει το όνομα οδού, τον αριθμό σπιτιού ή τη θυρίδα ταχυδρομείου.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός αν είναι ήδη  AddressType.Structured , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων και είναι προαιρετικό.

Τιμή: Η γραμμή διεύθυνσης 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Αποκτά το address line 2.

Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός αν είναι ήδη  AddressType.Structured , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η γραμμή διεύθυνσης 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


Λαμβάνει τον διψήφιο κωδικό χώρας ISO.

Ο κωδικός χώρας είναι υποχρεωτικός εκτός αν η πλήρης διεύθυνση περιέχει  null  ή emtpy τιμές.

Τιμή: Ο κωδικός χώρας ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Λαμβάνει τον αριθμό σπιτιού.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Ο αριθμός σπιτιού.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου.

Τιμή: Το όνομα.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


Λαμβάνει τον ταχυδρομικό κώδικα.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Ο ταχυδρομικός κώδικας.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Λαμβάνει την οδό.

Ο δρόμος πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Ο δρόμος.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Λαμβάνει την πόλη ή κωμόπολη.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η πόλη ή η κωμόπολη.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Λαμβάνει τον τύπο διεύθυνσης.

Ο τύπος διεύθυνσης ορίζεται αυτόματα είτε ορίζοντας το δρόμο / αριθμό σπιτιού είτε τη γραμμή διεύθυνσης 1 και 2. Πριν οριστούν τα πεδία, ο τύπος διεύθυνσης είναι *Απροσδιόριστο*. Εάν οριστούν πεδία και των δύο τύπων, ο τύπος διεύθυνσης γίνεται *Αντιφατικό*.

Τιμή: Ο τύπος διεύθυνσης.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Αποκτά τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


Ορίζει τη γραμμή διεύθυνσης 1.

Η γραμμή διεύθυνσης 1 περιέχει το όνομα οδού, τον αριθμό σπιτιού ή τη θυρίδα ταχυδρομείου.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός αν είναι ήδη  AddressType.Structured , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων και είναι προαιρετικό.

Τιμή: Η γραμμή διεύθυνσης 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Ορίζει τη γραμμή διεύθυνσης 2.

Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός αν είναι ήδη  AddressType.Structured , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η γραμμή διεύθυνσης 2.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Ορίζει τον διψήφιο κωδικό χώρας ISO.

Ο κωδικός χώρας είναι υποχρεωτικός εκτός αν η πλήρης διεύθυνση περιέχει  null  ή emtpy τιμές.

Τιμή: Ο κωδικός χώρας ISO.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Ορίζει τον αριθμό σπιτιού.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Ο αριθμός σπιτιού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου.

Τιμή: Το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Ορίζει τον ταχυδρομικό κώδικα.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Ο ταχυδρομικός κώδικας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Ορίζει την οδό.

Ο δρόμος πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Ο δρόμος.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Ορίζει την πόλη ή κωμόπολη.

Ο καθορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός αν είναι ήδη  AddressType.CombinedElements , σε αυτήν την περίπτωση γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η πόλη ή η κωμόπολη.

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


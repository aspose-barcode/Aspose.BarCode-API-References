---
title: Address
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Διεύθυνση του πιστωτή ή του οφειλέτη.
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

You can either set street, house number, postal code and town (type  *structured address* ) or address line 1 and 2 (type  *combined address elements* ). The type is automatically set once any of these fields is set. Before setting the fields, the address type is  *undetermined* . If fields of both types are set, the address type becomes  *conflicting* . Name and country code must always be set unless all fields are empty.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Address()](#Address--) | Creates instance of Address |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [clear()](#clear--) | Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [getAddressLine1()](#getAddressLine1--) | Λαμβάνει τη γραμμή διεύθυνσης 1. |
| [getAddressLine2()](#getAddressLine2--) | Λαμβάνει τη γραμμή διεύθυνσης 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | Λαμβάνει τον διψήφιο κωδικό χώρας ISO. |
| [getHouseNo()](#getHouseNo--) | Λαμβάνει τον αριθμό σπιτιού. |
| [getName()](#getName--) | Λαμβάνει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [getPostalCode()](#getPostalCode--) | Λαμβάνει τον ταχυδρομικό κώδικα. |
| [getStreet()](#getStreet--) | Λαμβάνει την οδό. |
| [getTown()](#getTown--) | Λαμβάνει την πόλη ή την κωμόπολη. |
| [getType()](#getType--) | Λαμβάνει τον τύπο διεύθυνσης. |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | Ορίζει τη γραμμή διεύθυνσης 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | Ορίζει τη γραμμή διεύθυνσης 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | Ορίζει τον διψήφιο κωδικό χώρας ISO. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | Ορίζει τον αριθμό σπιτιού. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | Ορίζει τον ταχυδρομικό κώδικα. |
| [setStreet(String value)](#setStreet-java.lang.String-) | Ορίζει την οδό. |
| [setTown(String value)](#setTown-java.lang.String-) | Ορίζει την πόλη ή την κωμόπολη. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Creates instance of Address

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει όλα τα πεδία και ορίζει τον τύπο σε  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο. |

**Returns:**
boolean -  true  εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


Λαμβάνει τη γραμμή διεύθυνσης 1.

Η γραμμή διεύθυνσης 1 περιέχει το όνομα οδού, τον αριθμό σπιτιού ή το ταχυδρομικό κουτί.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός εάν είναι ήδη  AddressType.Structured , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων και είναι προαιρετικό.

Τιμή: Η γραμμή διεύθυνσης 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


Λαμβάνει τη γραμμή διεύθυνσης 2.

Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός εάν είναι ήδη  AddressType.Structured , οπότε γίνεται  AddressType.Conflicting .

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

Ο κωδικός χώρας είναι υποχρεωτικός εκτός εάν η πλήρης διεύθυνση περιέχει  null  ή κενές τιμές.

Τιμή: Ο κωδικός χώρας ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


Λαμβάνει τον αριθμό σπιτιού.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

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

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Ο ταχυδρομικός κώδικας.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


Λαμβάνει την οδό.

Η οδός πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Η οδός.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


Λαμβάνει την πόλη ή την κωμόπολη.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η πόλη ή η κωμόπολη.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


Λαμβάνει τον τύπο διεύθυνσης.

Ο τύπος διεύθυνσης ορίζεται αυτόματα είτε ορίζοντας την οδό / αριθμό σπιτιού είτε τη γραμμή διεύθυνσης 1 και 2. Πριν οριστούν τα πεδία, ο τύπος διεύθυνσης είναι  *Undetermined* . Εάν οριστούν πεδία και των δύο τύπων, ο τύπος διεύθυνσης γίνεται  *Conflicting* .

Τιμή: Ο τύπος διεύθυνσης.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

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

Η γραμμή διεύθυνσης 1 περιέχει το όνομα οδού, τον αριθμό σπιτιού ή το ταχυδρομικό κουτί.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός εάν είναι ήδη  AddressType.Structured , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων και είναι προαιρετικό.

Τιμή: Η γραμμή διεύθυνσης 1.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


Ορίζει τη γραμμή διεύθυνσης 2.

Η γραμμή διεύθυνσης 2 περιέχει τον ταχυδρομικό κώδικα και την πόλη.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.CombinedElements  εκτός εάν είναι ήδη  AddressType.Structured , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για διευθύνσεις συνδυασμένων στοιχείων. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η γραμμή διεύθυνσης 2.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


Ορίζει τον διψήφιο κωδικό χώρας ISO.

Ο κωδικός χώρας είναι υποχρεωτικός εκτός εάν η πλήρης διεύθυνση περιέχει  null  ή κενές τιμές.

Τιμή: Ο κωδικός χώρας ISO.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


Ορίζει τον αριθμό σπιτιού.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Ο αριθμός σπιτιού.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα, είτε το όνομα και επώνυμο φυσικού προσώπου είτε το όνομα εταιρείας νομικού προσώπου.

Τιμή: Το όνομα.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


Ορίζει τον ταχυδρομικό κώδικα.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Ο ταχυδρομικός κώδικας.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


Ορίζει την οδό.

Η οδός πρέπει να καθορίζεται χωρίς αριθμό σπιτιού.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις και είναι προαιρετικό.

Τιμή: Η οδός.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


Ορίζει την πόλη ή την κωμόπολη.

Ο ορισμός αυτού του πεδίου ορίζει τον τύπο διεύθυνσης σε  AddressType.Structured  εκτός εάν είναι ήδη  AddressType.CombinedElements , οπότε γίνεται  AddressType.Conflicting .

Αυτό το πεδίο χρησιμοποιείται μόνο για δομημένες διευθύνσεις. Για αυτόν τον τύπο, είναι υποχρεωτικό.

Τιμή: Η πόλη ή η κωμόπολη.

**Parameters:**
| Parameter | Type | Περιγραφή |
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


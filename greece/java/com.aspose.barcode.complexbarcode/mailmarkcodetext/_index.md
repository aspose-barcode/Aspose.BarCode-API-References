---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα 4-κατάστασης Royal Mailmark."
type: docs
weight: 24
url: /el/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα 4-κατάστασης Royal Mailmark.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MailmarkCodetext . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο του barcode. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (Λιανική Δημοσίευση Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση Δικτύου) "9" - Τυπικό (Πρόσβαση Δικτύου) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργήστε codetext από τα δεδομένα Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Κενό ή Δοκιμή "1" \\u2013 Γράμμα "2" \\u2013 Μεγάλο Γράμμα |
| [getItemID()](#getItemID--) | Η μέγιστη τιμή είναι 99999999. |
| [getSupplychainID()](#getSupplychainID--) | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [getVersionID()](#getVersionID--) | Προς το παρόν "1" \\u2013 Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (Λιανική Δημοσίευση Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση Δικτύου) "9" - Τυπικό (Πρόσβαση Δικτύου) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Κενό ή Δοκιμή "1" \\u2013 Γράμμα "2" \\u2013 Μεγάλο Γράμμα |
| [setItemID(int value)](#setItemID-int-) | Η μέγιστη τιμή είναι 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Προς το παρόν "1" \\u2013 Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης  MailmarkCodetext .

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Λαμβάνει τον τύπο του barcode.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (Λιανική Δημοσίευση Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση Δικτύου) "9" - Τυπικό (Πρόσβαση Δικτύου)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Δημιουργήστε codetext από τα δεδομένα Mailmark.

**Returns:**
java.lang.String - Κατασκευασμένο κείμενο κώδικα
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που δηλώνει το διεθνές "XY11 " (σημειώστε τα 5 τελικά κενά) ή ένα μοτίβο χαρακτήρων που δηλώνει έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό ταχυδρομικό κώδικα, έναν εσωτερικό ταχυδρομικό κώδικα και ένα Πρόθεμα Σημείου Παράδοσης.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Κενό ή Δοκιμή "1" \\u2013 Γράμμα "2" \\u2013 Μεγάλο Γράμμα

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Η μέγιστη τιμή είναι 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Προς το παρόν "1" \\u2013 Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο codetext.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Κατασκευασμένο κείμενο κώδικα. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Κενό ή Δοκιμή "1" - 1C (Λιανική) "2" - 2C (Λιανική) "3" - 3C (Λιανική) "4" - Premium (Λιανική Δημοσίευση Mail) (για πιθανή μελλοντική χρήση) "5" - Αναβαλλόμενο (Λιανική) "6" - Αερο (Λιανική) (για πιθανή μελλοντική χρήση) "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση) "8" - Premium (Πρόσβαση Δικτύου) "9" - Τυπικό (Πρόσβαση Δικτύου)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF. Συμβολοσειρά εννέα χαρακτήρων που δηλώνει το διεθνές "XY11 " (σημειώστε τα 5 τελικά κενά) ή ένα μοτίβο χαρακτήρων που δηλώνει έναν εγχώριο κωδικό ταξινόμησης. Ένας εγχώριος κωδικός ταξινόμησης αποτελείται από έναν εξωτερικό ταχυδρομικό κώδικα, έναν εσωτερικό ταχυδρομικό κώδικα και ένα Πρόθεμα Σημείου Παράδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Κενό ή Δοκιμή "1" \\u2013 Γράμμα "2" \\u2013 Μεγάλο Γράμμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Η μέγιστη τιμή είναι 99999999.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Οι μέγιστες τιμές είναι 99 για το Barcode C και 999999 για το Barcode L.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Προς το παρόν "1" \\u2013 Για το barcode Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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


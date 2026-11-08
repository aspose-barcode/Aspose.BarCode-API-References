---
title: "SwissQRBill"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Δεδομένα λογαριασμού SwissQR"
type: docs
weight: 35
url: /el/java/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

Δεδομένα λογαριασμού SwissQR
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Δημιουργεί και ορίζει μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή τη συμβολοσειρά "RF" και τον έλεγχο modulo 97. |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το συγκεκριμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο. |
| [getAccount()](#getAccount--) | Λαμβάνει τον αριθμό λογαριασμού του πιστωτή. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. |
| [getAmount()](#getAmount--) | Λαμβάνει το ποσό πληρωμής. |
| [getBillInformation()](#getBillInformation--) | Λαμβάνει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | Λαμβάνει τη διεύθυνση του πιστωτή. |
| [getCurrency()](#getCurrency--) | Λαμβάνει το νόμισμα πληρωμής. |
| [getDebtor()](#getDebtor--) | Λαμβάνει τη διεύθυνση του οφειλέτη. |
| [getReference()](#getReference--) | Λαμβάνει την αναφορά πληρωμής του πιστωτή. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | Λαμβάνει το πρόσθετο αδόμητο μήνυμα. |
| [getVersion()](#getVersion--) | Λαμβάνει την έκδοση του πρότυπου τιμολογίου SwissQR. |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | Ορίζει τον αριθμό λογαριασμού του πιστωτή. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής. |
| [setAmount(double value)](#setAmount-double-) | Ορίζει το ποσό πληρωμής. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | Ορίζει τις πρόσθετες δομημένες πληροφορίες τιμολογίου. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | Ορίζει τη διεύθυνση του πιστωτή. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | Ορίζει το νόμισμα πληρωμής. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | Ορίζει τη διεύθυνση του οφειλέτη. |
| [setReference(String value)](#setReference-java.lang.String-) | Ορίζει την αναφορά πληρωμής του πιστωτή. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | Ορίζει το πρόσθετο αδόμητο μήνυμα. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | Ορίζει την έκδοση του πρότυπου τιμολογίου SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Δημιουργεί και ορίζει μια αναφορά πιστωτή ISO11649 από μια ακατέργαστη συμβολοσειρά προσθέτοντας στην αρχή τη συμβολοσειρά "RF" και τον έλεγχο modulo 97.

Τα κενά αφαιρούνται από την αναφορά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rawReference | java.lang.String | Η ακατέργαστη αναφορά. |

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
boolean -  true  εάν το καθορισμένο αντικείμενο είναι ίσο με το τρέχον αντικείμενο· διαφορετικά,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


Λαμβάνει τον αριθμό λογαριασμού του πιστωτή.

Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBAN τραπεζών της Ελβετίας ή του Λιχτενστάιν. Επιτρέπονται κενά στον αριθμό λογαριασμού.

Τιμή: Ο αριθμός λογαριασμού του πιστωτή.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής.

Μέγιστος επιτρεπόμενος αριθμός δύο σχημάτων με παραμέτρους.

Τιμή: Τα εναλλακτικά σχήματα πληρωμής.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


Λαμβάνει το ποσό πληρωμής.

Οι έγκυρες τιμές είναι μεταξύ 0,01 και 999.999.999,99.

Τιμή: Το ποσό πληρωμής.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


Λαμβάνει τις πρόσθετες δομημένες πληροφορίες του τιμολογίου.

Τιμή: Οι δομημένες πληροφορίες τιμολογίου.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


Λαμβάνει τη διεύθυνση του πιστωτή.

Τιμή: Η διεύθυνση του πιστωτή.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


Λαμβάνει το νόμισμα πληρωμής.

Οι έγκυρες τιμές είναι "CHF" και "EUR".

Τιμή: Το νόμισμα πληρωμής.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


Λαμβάνει τη διεύθυνση του οφειλέτη.

Ο οφειλέτης είναι προαιρετικός. Εάν παραλειφθεί, τόσο η ρύθμιση αυτού του πεδίου σε  null  όσο και η ρύθμιση μιας διεύθυνσης με όλες τις τιμές  null  ή κενές είναι εντάξει.

Τιμή: Η διεύθυνση του οφειλέτη.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


Λαμβάνει την αναφορά πληρωμής του πιστωτή.

Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, δηλαδή IBANs στην περιοχή CHxx30000xxxxxx έως CHxx31999xxxxx.

Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (αντιστοιχεί στη φόρμα αναφοράς ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx"). Και οι δύο μπορεί να περιέχουν κενά για μορφοποίηση.

Τιμή: Η αναφορά πληρωμής του πιστωτή.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


Λαμβάνει το πρόσθετο αδόμητο μήνυμα.

Τιμή: Το αδόμητο μήνυμα.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


Λαμβάνει την έκδοση του πρότυπου τιμολογίου SwissQR.

Τιμή: Η έκδοση του πρότυπου τιμολογίου SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


Ορίζει τον αριθμό λογαριασμού του πιστωτή.

Οι αριθμοί λογαριασμού πρέπει να είναι έγκυρα IBAN τραπεζών της Ελβετίας ή του Λιχτενστάιν. Επιτρέπονται κενά στον αριθμό λογαριασμού.

Τιμή: Ο αριθμός λογαριασμού του πιστωτή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


Λαμβάνει ή ορίζει τα εναλλακτικά σχήματα πληρωμής.

Μέγιστος επιτρεπόμενος αριθμός δύο σχημάτων με παραμέτρους.

Τιμή: Τα εναλλακτικά σχήματα πληρωμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


Ορίζει το ποσό πληρωμής.

Οι έγκυρες τιμές είναι μεταξύ 0,01 και 999.999.999,99.

Τιμή: Το ποσό πληρωμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


Ορίζει τις πρόσθετες δομημένες πληροφορίες τιμολογίου.

Τιμή: Οι δομημένες πληροφορίες τιμολογίου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


Ορίζει τη διεύθυνση του πιστωτή.

Τιμή: Η διεύθυνση του πιστωτή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


Ορίζει το νόμισμα πληρωμής.

Οι έγκυρες τιμές είναι "CHF" και "EUR".

Τιμή: Το νόμισμα πληρωμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


Ορίζει τη διεύθυνση του οφειλέτη.

Ο οφειλέτης είναι προαιρετικός. Εάν παραλειφθεί, τόσο η ρύθμιση αυτού του πεδίου σε  null  όσο και η ρύθμιση μιας διεύθυνσης με όλες τις τιμές  null  ή κενές είναι εντάξει.

Τιμή: Η διεύθυνση του οφειλέτη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


Ορίζει την αναφορά πληρωμής του πιστωτή.

Η αναφορά είναι υποχρεωτική για τα SwissQR IBAN, δηλαδή IBANs στην περιοχή CHxx30000xxxxxx έως CHxx31999xxxxx.

Εάν καθοριστεί, η αναφορά πρέπει να είναι είτε μια έγκυρη αναφορά SwissQR (αντιστοιχεί στη φόρμα αναφοράς ISR) είτε μια έγκυρη αναφορά πιστωτή σύμφωνα με το ISO 11649 ("RFxxxx"). Και οι δύο μπορεί να περιέχουν κενά για μορφοποίηση.

Τιμή: Η αναφορά πληρωμής του πιστωτή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


Ορίζει το πρόσθετο αδόμητο μήνυμα.

Τιμή: Το αδόμητο μήνυμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


Ορίζει την έκδοση του πρότυπου τιμολογίου SwissQR.

Τιμή: Η έκδοση του πρότυπου τιμολογίου SwissQR.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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


---
title: "Mailmark2DCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark."
type: docs
weight: 23
url: /el/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Δημιουργεί προεπιλεγμένη εμφάνιση της κλάσης Mailmark2DCodetext. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί κείμενο κώδικα από τα δεδομένα Mailmark. |
| [getCustomerContent()](#getCustomerContent--) | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Λειτουργία κωδικοποίησης του barcode Datamatrix. |
| [getDataMatrixType()](#getDataMatrixType--) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. |
| [getInformationTypeID()](#getInformationTypeID--) | Αναγνωρίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
| [getItemID()](#getItemID--) | Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Περιέχει τον ταχυδρομικό κώδικα Return to Sender αλλά χωρίς DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Αναγνωρίζει την μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
| [getUPUCountryID()](#getUPUCountryID--) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [getVersionID()](#getVersionID--) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |
| [getclass()](#getclass--) | Καθορίζει την κατηγορία του αντικειμένου. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο κείμενο κώδικα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Λειτουργία κωδικοποίησης του barcode Datamatrix. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Περιέχει τον ταχυδρομικό κώδικα της διεύθυνσης παράδοσης με DPS. Εάν είναι ενδοχώρα, ο ταχυδρομικός κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Αναγνωρίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. |
| [setItemID(int value)](#setItemID-int-) | Αναγνωρίζει το μοναδικό αντικείμενο εντός του Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Περιέχει τον ταχυδρομικό κώδικα Return to Sender αλλά χωρίς DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Αναγνωρίζει την μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |
| [setclass(String value)](#setclass-java.lang.String-) | Καθορίζει την κατηγορία του αντικειμένου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Δημιουργεί προεπιλεγμένη εμφάνιση της κλάσης Mailmark2DCodetext.

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


Λαμβάνει τον τύπο barcode.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Δημιουργεί κείμενο κώδικα από τα δεδομένα Mailmark.

**Returns:**
java.lang.String - Κατασκευασμένο codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

**Returns:**
java.lang.String - Περιεχόμενο πελάτη
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS. Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

**Returns:**
java.lang.String - ο Ταχυδρομικός Κώδικας της Διεύθυνσης Παράδοσης με DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Καθορίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Μη ταξινομημένα 'A' - Ηλεκτρονική Ταχυδρόμηση 'B' - Φραγκάρισμα 'C' - Συγκέντρωση

**Returns:**
java.lang.String - Αναγνωριστικό τύπου πληροφορίας
### getItemID() {#getItemID--}
```
public int getItemID()
```


Καθορίζει το μοναδικό αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας. Κάθε barcode Mailmark πρέπει να περιέχει ένα αναγνωριστικό ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

**Returns:**
int - αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται.

**Returns:**
java.lang.String - Σημαία RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα χωρίς DPS. Ο κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

**Returns:**
java.lang.String - Ταχυδρομικός Κώδικας Επιστροφής στον Αποστολέα χωρίς DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Καθορίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

**Returns:**
int - Αναγνωριστικό εφοδιαστικής αλυσίδας
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.

**Returns:**
java.lang.String - Αναγνωριστικό χώρας
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Καθορίζει την έκδοση του barcode ανάλογα με κάθε Αναγνωριστικό Τύπου Πληροφορίας. Έγκυρες τιμές: Προς το παρόν '1'. '0' και '2' έως '9' και 'A' έως 'Z' διατηρούνται για πιθανή μελλοντική χρήση.

**Returns:**
java.lang.String - Αναγνωριστικό έκδοσης
### getclass() {#getclass--}
```
public String getclass()
```


Καθορίζει την κατηγορία του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Οικονομική (Λιανική) '5' - Αναβαλλόμενη (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

**Returns:**
java.lang.String - κατηγορία του αντικειμένου
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


Αρχικοποιεί τα δεδομένα Mailmark από το κατασκευασμένο κείμενο κώδικα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Κατασκευασμένο codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες Τύπος 9: 45 χαρακτήρες Τύπος 29: 25 χαρακτήρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Περιεχόμενο πελάτη |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.C40.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Λειτουργία κωδικοποίησης του barcode Datamatrix. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Μέγεθος barcode Data Matrix |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS. Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων. Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | ο Ταχυδρομικός Κώδικας της Διεύθυνσης Παράδοσης με DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Καθορίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Μη ταξινομημένα 'A' - Ηλεκτρονική Ταχυδρόμηση 'B' - Φραγκάρισμα 'C' - Συγκέντρωση

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Αναγνωριστικό τύπου πληροφορίας |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Καθορίζει το μοναδικό αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας. Κάθε barcode Mailmark πρέπει να περιέχει ένα αναγνωριστικό ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | αντικείμενο εντός του Αναγνωριστικού Αλυσίδας Εφοδιασμού |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα χωρίς DPS. Ο κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Επιστροφή στον Αποστολέα Ταχυδρομικός Κώδικας αλλά χωρίς DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Καθορίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Αναγνωριστικό Αλυσίδας Εφοδιασμού |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Αναγνωριστικό Χώρας |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Καθορίζει την έκδοση του barcode ανάλογα με κάθε Αναγνωριστικό Τύπου Πληροφορίας. Έγκυρες τιμές: Προς το παρόν '1'. '0' και '2' έως '9' και 'A' έως 'Z' διατηρούνται για πιθανή μελλοντική χρήση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Αναγνωριστικό Έκδοσης |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Καθορίζει την κατηγορία του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Οικονομική (Λιανική) '5' - Αναβαλλόμενη (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | κλάση του αντικειμένου |

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


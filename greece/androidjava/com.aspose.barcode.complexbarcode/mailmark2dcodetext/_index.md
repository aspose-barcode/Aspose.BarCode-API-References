---
title: Mailmark2DCodetext
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα Royal Mail 2D Mailmark.
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
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Επιστροφή στον Αποστολέα ζητείται. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. |
| [getSupplyChainID()](#getSupplyChainID--) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
| [getUPUCountryID()](#getUPUCountryID--) | Αναγνωρίζει το Αναγνωριστικό Χώρας UPU. Μέγιστο μήκος: 4 χαρακτήρες. |
| [getVersionID()](#getVersionID--) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Αναγνωριστικό Τύπου Πληροφορίας. |
| [getclass()](#getclass--) | Αναγνωρίζει την κατηγορία του αντικειμένου. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Επιστροφή στον Αποστολέα ζητείται. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | Αναγνωρίζει το Αναγνωριστικό Χώρας UPU. Μέγιστο μήκος: 4 χαρακτήρες. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Αναγνωριστικό Τύπου Πληροφορίας. |
| [setclass(String value)](#setclass-java.lang.String-) | Αναγνωρίζει την κατηγορία του αντικειμένου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - Constructed codetext
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες, Τύπος 9: 45 χαρακτήρες, Τύπος 29: 25 χαρακτήρες.

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


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS. Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων: Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

**Returns:**
java.lang.String - ο Ταχυδρομικός Κώδικας της Διεύθυνσης Παράδοσης με DPS
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


Αναγνωρίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Μη ταξινομημένα 'A' - Ηλεκτρονική Ταχυδρομική Αποστολή 'B' - Φραγκάρισμα 'C' - Συγκέντρωση

**Returns:**
java.lang.String - Αναγνωριστικό τύπου πληροφορίας
### getItemID() {#getItemID--}
```
public int getItemID()
```


Αναγνωρίζει το μοναδικό αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας. Κάθε barcode Mailmark πρέπει να φέρει ένα Αναγνωριστικό ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

**Returns:**
int - αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Επιστροφή στον Αποστολέα ζητείται.

**Returns:**
java.lang.String - Σημαία RTS
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. Ο Κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

**Returns:**
java.lang.String - Ταχυδρομικός Κώδικας Επιστροφής στον Αποστολέα χωρίς DPS
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

**Returns:**
int - Αναγνωριστικό εφοδιαστικής αλυσίδας
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


Αναγνωρίζει το Αναγνωριστικό Χώρας UPU. Μέγιστο μήκος: 4 χαρακτήρες.

**Returns:**
java.lang.String - Αναγνωριστικό χώρας
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Αναγνωριστικό Τύπου Πληροφορίας. Έγκυρες τιμές: Προς το παρόν '1'. '0' και '2' έως '9' και 'A' έως 'Z' διατηρούνται για ενδεχόμενη μελλοντική χρήση.

**Returns:**
java.lang.String - Αναγνωριστικό έκδοσης
### getclass() {#getclass--}
```
public String getclass()
```


Αναγνωρίζει την κατηγορία του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Οικονομική (Λιανική) '5' - Αναβαλλόμενη (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

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


Initializes Mailmark data from constructed codetext.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Constructed codetext. |

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


Προαιρετικός χώρος για χρήση από τον πελάτη. Μέγιστο μήκος ανά τύπο: Τύπος 7: 6 χαρακτήρες, Τύπος 9: 45 χαρακτήρες, Τύπος 29: 25 χαρακτήρες.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Customer content |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Encode mode of Datamatrix barcode. Default value: EncodeMode.C40.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Size of Data Matrix barcode |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS. Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων: Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες) Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες). Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | the Postcode of the Delivery Address with DPS |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


Αναγνωρίζει το φορτίο του barcode Royal Mail Mailmark για κάθε τύπο προϊόντος. Έγκυρες τιμές: '0' - Ενδοχώρα Ταξινομημένα & Μη ταξινομημένα 'A' - Ηλεκτρονική Ταχυδρομική Αποστολή 'B' - Φραγκάρισμα 'C' - Συγκέντρωση

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Information type ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Αναγνωρίζει το μοναδικό αντικείμενο εντός του Αναγνωριστικού Εφοδιαστικής Αλυσίδας. Κάθε barcode Mailmark πρέπει να φέρει ένα Αναγνωριστικό ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες. Μέγιστη τιμή: 99999999.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int | item within the Supply Chain ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


Σημαία που υποδεικνύει ποιο επίπεδο της υπηρεσίας Επιστροφή στον Αποστολέα ζητείται.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


Περιέχει τον Ταχυδρομικό Κώδικα Επιστροφής στον Αποστολέα αλλά χωρίς DPS. Ο Κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Return to Sender Post Code but no DPS |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή. Μέγιστη τιμή: 9999999.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Supply chain ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


Αναγνωρίζει το Αναγνωριστικό Χώρας UPU. Μέγιστο μήκος: 4 χαρακτήρες.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Country ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Αναγνωριστικό Τύπου Πληροφορίας. Έγκυρες τιμές: Προς το παρόν '1'. '0' και '2' έως '9' και 'A' έως 'Z' διατηρούνται για ενδεχόμενη μελλοντική χρήση.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Version ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


Αναγνωρίζει την κατηγορία του αντικειμένου. Έγκυρες τιμές: '1' - 1C (Λιανική) '2' - 2C (Λιανική) '3' - Οικονομική (Λιανική) '5' - Αναβαλλόμενη (Λιανική) '8' - Premium (Πρόσβαση Δικτύου) '9' - Standard (Πρόσβαση Δικτύου)

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | class of the item |

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


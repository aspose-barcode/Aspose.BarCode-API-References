---
title: QRExtendedParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode
type: docs
weight: 42
url: /el/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode

Αυτό το παράδειγμα δείχνει πώς να λάβετε δεδομένα QR Structured Append

```
{
```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Έκδοση του αναγνωρισμένου MicroQR Code. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Αποκτά το δείκτη του barcode σε λειτουργία QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Αποκτά την ποσότητα των barcode σε λειτουργία QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Λαμβάνει τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR. |
| [getQRVersion()](#getQRVersion--) | Έκδοση του αναγνωρισμένου κώδικα QR. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Έκδοση του αναγνωρισμένου κώδικα RectMicroQR. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Αποκτά το δείκτη του barcode σε λειτουργία QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Αποκτά την ποσότητα των barcode σε λειτουργία QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Λαμβάνει τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR. |
| [getVersion()](#getVersion--) | Έκδοση του αναγνωρισμένου κώδικα QR. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) είναι ίση με τη δεύτερη. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) διαφέρει από τη δεύτερη. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Έκδοση του αναγνωρισμένου κώδικα MicroQR. Από M1 έως M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Λαμβάνει τον δείκτη του barcode λειτουργίας προσάρτησης δομημένου QR. Ο δείκτης ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - ο δείκτης του barcode λειτουργίας προσάρτησης δομημένου QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Λαμβάνει την ποσότητα των barcode λειτουργίας προσάρτησης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - η ποσότητα των barcode λειτουργίας προσάρτησης δομημένου QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Λαμβάνει τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Ο δείκτης του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Έκδοση του αναγνωρισμένου κώδικα QR. Από Version1 έως Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Έκδοση του αναγνωρισμένου κώδικα RectMicroQR. Από R7x43 έως R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Λαμβάνει τον δείκτη του barcode λειτουργίας προσάρτησης δομημένου QR. Ο δείκτης ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - ο δείκτης του barcode λειτουργίας προσάρτησης δομημένου QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Λαμβάνει την ποσότητα των barcode λειτουργίας προσάρτησης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - η ποσότητα των barcode λειτουργίας προσάρτησης δομημένου QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Λαμβάνει τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Ο δείκτης του barcode λειτουργίας προσάρτησης δομημένου QR.

**Returns:**
int - τα δεδομένα parity της λειτουργίας προσάρτησης δομημένου QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Έκδοση του αναγνωρισμένου κώδικα QR. Από Version1 έως Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές

Τιμή: Επιστρέφει  **true**  εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές· διαφορετικά,  **false** .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) είναι ίση με τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει την ίδια τιμή με τη δεύτερη· διαφορετικά,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) διαφέρει από τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει διαφορετική τιμή από τη δεύτερη· διαφορετικά,  **false** .
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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


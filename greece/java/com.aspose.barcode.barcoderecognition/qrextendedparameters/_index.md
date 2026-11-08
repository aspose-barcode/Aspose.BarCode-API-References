---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Αποθηκεύει πληροφορίες QR Structured Append ενός αναγνωρισμένου barcode"
type: docs
weight: 38
url: /el/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει πληροφορίες QR Structured Append ενός αναγνωρισμένου barcode

Αυτό το παράδειγμα δείχνει πώς να λάβετε δεδομένα QR Structured Append

```
{
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Έκδοση του αναγνωρισμένου MicroQR Code. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Έκδοση του αναγνωρισμένου RectMicroQR Code. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Λαμβάνει τον δείκτη του QR barcode σε λειτουργία structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Λαμβάνει την ποσότητα των QR barcode σε λειτουργία structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Λαμβάνει τα parity δεδομένα του QR barcode σε λειτουργία structured append. |
| [getVersion()](#getVersion--) | Έκδοση του αναγνωρισμένου QR Code. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
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
| Παράμετρος | Τύπος | Περιγραφή |
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


Έκδοση του αναγνωρισμένου MicroQR Code. Από M1 έως M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Έκδοση του αναγνωρισμένου RectMicroQR Code. Από R7x43 έως R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Λαμβάνει τον δείκτη του QR barcode σε λειτουργία structured append. Ο δείκτης ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα των QR barcode σε λειτουργία structured append.

**Returns:**
int - ο δείκτης του QR barcode σε λειτουργία structured append.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Λαμβάνει την ποσότητα των QR barcode σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Η ποσότητα των QR barcode σε λειτουργία structured append.

**Returns:**
int - η ποσότητα των QR barcode σε λειτουργία structured append.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Λαμβάνει τα parity δεδομένα του QR barcode σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Ο δείκτης του QR barcode σε λειτουργία structured append.

**Returns:**
int - τα parity δεδομένα του QR barcode σε λειτουργία structured append.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Έκδοση του αναγνωρισμένου QR Code. Από Version1 έως Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές

Τιμή: Επιστρέφει  **true**  εάν όλες οι παράμετροι έχουν μόνο προεπιλεγμένες τιμές· διαφορετικά,  **false** .

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


---
title: "QrParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι QR."
type: docs
weight: 62
url: /el/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Παράμετροι QR.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για το barcode QR, MicroQR και RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Έκδοση του MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Έκδοση του RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Παράμετροι δομημένης προσθήκης QR. |
| [getVersion()](#getVersion--) | Έκδοση του QR Code. Από Version1 έως Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για το barcode QR, MicroQR και RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Έκδοση του MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | Έκδοση του RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | Παράμετροι δομημένης προσθήκης QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | Έκδοση του QR Code. Από Version1 έως Version40. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από το MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τα barcodes QR και RectMicroQR.

Εάν είναι ψευδές, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR.

Εάν είναι αληθές, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα.

Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 σε επίπεδο byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

**Returns:**
boolean - μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τα barcodes QR και RectMicroQR.
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για το barcode QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τα barcodes MicroQR και RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Έκδοση του QR Code. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. Δεν υποστηρίζεται από το MicroQR.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τα barcodes QR και RectMicroQR.

Εάν είναι ψευδές, οι διαχωριστές GS1 μπορεί να κωδικοποιηθούν ως '%' σε αλφαριθμητική λειτουργία σύμφωνα με την προδιαγραφή QR.

Εάν είναι αληθές, οι διαχωριστές ομάδας GS1 κωδικοποιούνται σε λειτουργία Byte ως ο χαρακτήρας 0x1D, και οι χαρακτήρες '%' επίσης κωδικοποιούνται σε λειτουργία Byte για να διατηρηθούν ως δεδομένα.

Αυτή η επιλογή μπορεί να βελτιώσει τη συμβατότητα με αποκωδικοποιητές που αναμένουν διαχωριστές ομάδας GS1 σε επίπεδο byte και αποτρέπει τους χαρακτήρες δεδομένων '%' από το να ερμηνευτούν ως διαχωριστές GS1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | μια τιμή που υποδεικνύει εάν οι ειδικοί χαρακτήρες GS1 πρέπει να κωδικοποιηθούν σε λειτουργία Byte για τα barcodes QR και RectMicroQR. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για το barcode QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε QRErrorLevel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Έκδοση του MicroQR Code. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Έκδοση του RectMicroQR Code. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τα barcodes MicroQR και RectMicroQR.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Έκδοση του QR Code. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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


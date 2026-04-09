---
title: QrParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Παράμετροι QR.
type: docs
weight: 64
url: /el/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

Παράμετροι QR.
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για τους γραμμωτούς κώδικες QR, MicroQR και RectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Έκδοση του MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getQrEncodeMode()](#getQrEncodeMode--) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. |
| [getQrEncodeType()](#getQrEncodeType--) | Λειτουργία επιλογής QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για τους γραμμωτούς κώδικες QR, MicroQR και RectMicroQR. |
| [getQrVersion()](#getQrVersion--) | Έκδοση του QR Code. Από Version1 έως Version40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | Έκδοση του RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | Παράμετροι δομημένης προσθήκης QR. |
| [getVersion()](#getVersion--) | Έκδοση του QR Code. Από Version1 έως Version40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon για τους γραμμωτούς κώδικες QR, MicroQR και RectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | Έκδοση του MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | Λειτουργία επιλογής QR / MicroQR. |
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
| Parameter | Type | Περιγραφή |
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


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη γραμμωτού κώδικα για λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές κωδικοποίησης των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. Δεν υποστηρίζεται από MicroQR.

**Returns:**
int
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


Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon για τους κώδικες QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Έκδοση κώδικα MicroQR. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη γραμμωτού κώδικα για λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές κωδικοποίησης των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. Δεν υποστηρίζεται από MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon για τους κώδικες QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


Έκδοση κώδικα QR. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


Έκδοση κώδικα RectMicroQR. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τους κώδικες MicroQR και RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Έκδοση κώδικα QR. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public native int hashCode()
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη γραμμωτού κώδικα για λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές κωδικοποίησης των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. Δεν υποστηρίζεται από MicroQR.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


Τύπος συμβολισμού QR της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


Επίπεδο διόρθωσης σφαλμάτων Reed‑Solomon για τους κώδικες QR, MicroQR και RectMicroQR. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. Δείτε το QRErrorLevel.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


Έκδοση κώδικα MicroQR. Από την έκδοση M1 έως την έκδοση M4. Η προεπιλεγμένη τιμή είναι MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


Λειτουργία επιλογέα QR / MicroQR. Επιλέξτε ForceQR για τυπικά σύμβολα QR, Auto για MicroQR.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


Έκδοση κώδικα RectMicroQR. Από την έκδοση R7x59 έως την έκδοση R17x139. Η προεπιλεγμένη τιμή είναι RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


Παράμετροι δομημένης προσθήκης QR. Η λειτουργία δομημένης προσθήκης δεν υποστηρίζεται από τους κώδικες MicroQR και RectMicroQR.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


Έκδοση κώδικα QR. Από Version1 έως Version40. Η προεπιλεγμένη τιμή είναι QRVersion.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
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


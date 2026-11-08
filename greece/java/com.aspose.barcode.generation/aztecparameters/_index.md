---
title: "AztecParameters"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Παράμετροι Aztec."
type: docs
weight: 12
url: /el/java/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

Παράμετροι Aztec.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Λαμβάνει την κωδικοποίηση ECI. |
| [getEncodeMode()](#getEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. |
| [getErrorLevel()](#getErrorLevel--) | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. |
| [getLayersCount()](#getLayersCount--) | Λαμβάνει τον αριθμό των στρωμάτων του συμβόλου Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). |
| [getSymbolMode()](#getSymbolMode--) | Λαμβάνει μια λειτουργία συμβόλου Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει την κωδικοποίηση ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | Ορίζει τον αριθμό των στρωμάτων του συμβόλου Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | Ορίζει μια λειτουργία συμβόλου Aztec. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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


Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1.

**Returns:**
int - κωδικοποίηση ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Λαμβάνει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - μια λειτουργία κωδικοποίησης Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Λαμβάνει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός επιπέδων πρέπει να βρίσκεται στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (auto).

**Returns:**
int - αριθμός επιπέδων του συμβόλου Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Αναγνωριστικό Barcode για τη λειτουργία Structured Append του barcode Aztec. Το αναγνωριστικό Barcode πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Λαμβάνει μια λειτουργία Aztec Symbol. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

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


Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το AztecEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Κωδικοποίηση ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Ορίζει μια λειτουργία κωδικοποίησης Aztec. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.barcode.generation.AztecEncodeMode | μια λειτουργία κωδικοποίησης Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec. Η τιμή πρέπει να είναι μεταξύ 5 και 95.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Ορίζει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός επιπέδων πρέπει να βρίσκεται στο εύρος από 1 έως 3 για τη λειτουργία Compact και στο εύρος από 1 έως 32 για τη λειτουργία Full Range. Προεπιλεγμένη τιμή: 0 (auto).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | αριθμός επιπέδων του συμβόλου Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Αναγνωριστικό Barcode για τη λειτουργία Structured Append του barcode Aztec. Το αναγνωριστικό Barcode πρέπει να είναι στο εύρος από 1 έως τον αριθμό των barcode. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Αριθμός barcode για τη λειτουργία Structured Append του barcode Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά. Προεπιλεγμένη τιμή: κενή συμβολοσειρά

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Ορίζει μια λειτουργία Aztec Symbol. Προεπιλεγμένη τιμή: AztecSymbolMode.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | μια λειτουργία Aztec Symbol. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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


---
title: "DotCodeParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι DotCode."
type: docs
weight: 35
url: /el/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

Παράμετροι DotCode.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Αναγνωρίζει τον αριθμό των στηλών. |
| [getECIEncoding()](#getECIEncoding--) | Αναγνωρίζει την κωδικοποίηση ECI. |
| [getEncodeMode()](#getEncodeMode--) | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. |
| [getRows()](#getRows--) | Αναγνωρίζει τον αριθμό των γραμμών. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Αναγνωρίζει τον αριθμό των barcode λειτουργίας δομημένης προσθήκης DotCode. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setColumns(int value)](#setColumns-int-) | Αναγνωρίζει τον αριθμό των στηλών. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Αναγνωρίζει την κωδικοποίηση ECI. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. |
| [setRows(int value)](#setRows-int-) | Αναγνωρίζει τον αριθμό των γραμμών. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Αναγνωρίζει τον αριθμό των barcode λειτουργίας δομημένης προσθήκης DotCode. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Αναγνωρίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Αναγνωρίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Αναγνωρίζει τον αριθμό των barcode λειτουργίας δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Returns:**
int
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


Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Αναγνωρίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Αναγνωρίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Αναγνωρίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών και του αριθμού των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Αναγνωρίζει τον αριθμό των barcode λειτουργίας δομημένης προσθήκης DotCode. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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


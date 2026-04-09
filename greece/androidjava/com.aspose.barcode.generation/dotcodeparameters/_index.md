---
title: DotCodeParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: DotCode parameters.
type: docs
weight: 36
url: /el/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode parameters.
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


Καθορίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Καθορίζει το αναγνωριστικό (ID) του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Προεπιλεγμένη τιμή είναι -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Καθορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


Καθορίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Καθορίζει το αναγνωριστικό (ID) του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Προεπιλεγμένη τιμή είναι -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. Η προεπιλεγμένη τιμή είναι false.

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Καθορίζει τον αριθμό των στηλών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των στηλών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


Καθορίζει το αναγνωριστικό (ID) του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Προεπιλεγμένη τιμή είναι -1.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Καθορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το DotCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


Καθορίζει τη λειτουργία κωδικοποίησης DotCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. Η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Καθορίζει τον αριθμό των γραμμών. Το άθροισμα του αριθμού των γραμμών συν τον αριθμό των στηλών ενός συμβόλου DotCode πρέπει να είναι περιττό. Ο αριθμός των γραμμών πρέπει να είναι τουλάχιστον 5. Προεπιλεγμένη τιμή: -1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Καθορίζει το αναγνωριστικό (ID) του barcode σε λειτουργία δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Προεπιλεγμένη τιμή είναι -1.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Καθορίζει τον αριθμό των barcode σε λειτουργία δομημένης προσθήκης DotCode. Προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

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


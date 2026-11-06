---
title: "MaxiCodeParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι MaxiCode."
type: docs
weight: 55
url: /el/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

Παράμετροι MaxiCode.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Λαμβάνει την κωδικοποίηση ECI. |
| [getEncodeMode()](#getEncodeMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getMode()](#getMode--) | Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Λαμβάνει ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Λαμβάνει τον αριθμό των barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει την κωδικοποίηση ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Ορίζει ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Ορίζει τον αριθμό των barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη αναπαράσταση συμβολοσειράς αυτού του [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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


Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Returns:**
int - κωδικοποίηση ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


Λαμβάνει μια λειτουργία κωδικοποίησης MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Λαμβάνει ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης. Το ID πρέπει να είναι τιμή μεταξύ 1 και 8. Προεπιλεγμένη τιμή: 0

**Returns:**
int - ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Λαμβάνει τον αριθμό των barcode MaxiCode σε λειτουργία δομημένης προσθήκης. Ο αριθμός πρέπει να είναι τιμή μεταξύ 2 και 8 (μέγιστος αριθμός barcode). Προεπιλεγμένη τιμή: -1

**Returns:**
int - ένας αριθμός barcode MaxiCode σε λειτουργία δομημένης προσθήκης.
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


Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το MaxiCodeEncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Κωδικοποίηση ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Ορίζει μια λειτουργία κωδικοποίησης MaxiCode. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | μια λειτουργία κωδικοποίησης MaxiCode. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


Ορίζει μια λειτουργία κωδικοποίησης MaxiCode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | μια λειτουργία κωδικοποίησης MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Ορίζει ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης. Το ID πρέπει να είναι τιμή μεταξύ 1 και 8. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ένα αναγνωριστικό barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Ορίζει τον αριθμό των barcode MaxiCode σε λειτουργία δομημένης προσθήκης. Ο αριθμός πρέπει να είναι τιμή μεταξύ 2 και 8 (μέγιστος αριθμός barcode). Προεπιλεγμένη τιμή: -1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | ο αριθμός των barcode MaxiCode σε λειτουργία δομημένης προσθήκης. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη αναπαράσταση συμβολοσειράς αυτού του [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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


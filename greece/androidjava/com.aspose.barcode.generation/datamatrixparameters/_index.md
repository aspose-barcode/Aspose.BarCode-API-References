---
title: "DataMatrixParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι DataMatrix."
type: docs
weight: 33
url: /el/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

Παράμετροι DataMatrix.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Λαμβάνει την κωδικοποίηση ECI. |
| [getEccType()](#getEccType--) | Αποκτά έναν τύπο ECC του Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Λειτουργία κωδικοποίησης του barcode Datamatrix. |
| [getMacroCharacters()](#getMacroCharacters--) | Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getVersion()](#getVersion--) | Αποκτά το μέγεθος συμβόλου του Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει την κωδικοποίηση ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Ορίζει έναν τύπο ECC του Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Λειτουργία κωδικοποίησης του barcode Datamatrix. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Ορίζει το μέγεθος συμβόλου του Datamatrix. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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


Αποκτά κωδικοποίηση ECI. Χρησιμοποιείται όταν το EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Returns:**
int - κωδικοποίηση ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Αποκτά έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getEncodeMode() {#getEncodeMode--}
```
public final DataMatrixEncodeMode getEncodeMode()
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με DataMatrixEccType.Ecc200 ή DataMatrixEccType.EccAuto. Δεν μπορούν να χρησιμοποιηθούν με EncodeTypes.GS1DataMatrix. Προεπιλεγμένη τιμή: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Αριθμός γραμμωτών κωδίκων για τη λειτουργία Structured Append του κωδικού Datamatrix. Προεπιλεγμένη τιμή: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κωδικού Datamatrix. Προεπιλεγμένη τιμή: 0

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Λαμβάνει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Χρησιμοποιείται για να καθοδηγήσει το αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. Προεπιλεγμένη τιμή: false

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


Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Κωδικοποίηση ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Ορίζει έναν τύπο ECC για Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ένας τύπος ECC για Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με DataMatrixEccType.Ecc200 ή DataMatrixEccType.EccAuto. Δεν μπορούν να χρησιμοποιηθούν με EncodeTypes.GS1DataMatrix. Προεπιλεγμένη τιμή: MacroCharacters.None.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Χρησιμοποιείται για να καθοδηγήσει το αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. Προεπιλεγμένη τιμή: false

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Αριθμός γραμμωτών κωδίκων για τη λειτουργία Structured Append του κωδικού Datamatrix. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κωδικού Datamatrix. Προεπιλεγμένη τιμή: 0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Ορίζει το μέγεθος συμβόλου Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | ένα μέγεθος συμβόλου Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).
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


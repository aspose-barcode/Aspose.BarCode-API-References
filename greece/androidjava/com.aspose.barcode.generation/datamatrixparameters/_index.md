---
title: DataMatrixParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: DataMatrix parameters.
type: docs
weight: 34
url: /el/androidjava/com.aspose.barcode.generation/datamatrixparameters/
---
**Inheritance:**
java.lang.Object
```
public class DataMatrixParameters
```

DataMatrix parameters.
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Αριθμός στηλών. |
| [getDataMatrixEcc()](#getDataMatrixEcc--) | Λαμβάνει έναν τύπο ECC του Datamatrix. |
| [getDataMatrixEncodeMode()](#getDataMatrixEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixVersion()](#getDataMatrixVersion--) | Λαμβάνει το μέγεθος συμβόλου του Datamatrix. |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getEccType()](#getEccType--) | Λαμβάνει έναν τύπο ECC του Datamatrix. |
| [getEncodeMode()](#getEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getMacroCharacters()](#getMacroCharacters--) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [getRows()](#getRows--) | Αριθμός σειρών. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. |
| [getVersion()](#getVersion--) | Λαμβάνει το μέγεθος συμβόλου του Datamatrix. |
| [hashCode()](#hashCode--) |  |
| [isReaderProgramming()](#isReaderProgramming--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setColumns(int value)](#setColumns-int-) | Αριθμός στηλών. |
| [setDataMatrixEcc(DataMatrixEccType value)](#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-) | Ορίζει έναν τύπο ECC του Datamatrix. |
| [setDataMatrixEncodeMode(DataMatrixEncodeMode value)](#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixVersion(DataMatrixVersion value)](#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Ορίζει το μέγεθος συμβόλου του Datamatrix. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Ορίζει κωδικοποίηση ECI. |
| [setEccType(DataMatrixEccType value)](#setEccType-com.aspose.barcode.generation.DataMatrixEccType-) | Ορίζει έναν τύπο ECC του Datamatrix. |
| [setEncodeMode(DataMatrixEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [setReaderProgramming(boolean value)](#setReaderProgramming-boolean-) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [setRows(int value)](#setRows-int-) | Αριθμός σειρών. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setStructuredAppendFileId(int value)](#setStructuredAppendFileId-int-) | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. |
| [setVersion(DataMatrixVersion value)](#setVersion-com.aspose.barcode.generation.DataMatrixVersion-) | Ορίζει το μέγεθος συμβόλου του Datamatrix. |
| [toString()](#toString--) | Επιστρέφει μια ευανάγνωστη αναπαράσταση συμβολοσειράς αυτού του [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters). |
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


Αριθμός στηλών.

**Returns:**
int
### getDataMatrixEcc() {#getDataMatrixEcc--}
```
public final DataMatrixEccType getDataMatrixEcc()
```


Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Returns:**
[DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) - a Datamatrix ECC type.
### getDataMatrixEncodeMode() {#getDataMatrixEncodeMode--}
```
public final DataMatrixEncodeMode getDataMatrixEncodeMode()
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### getDataMatrixVersion() {#getDataMatrixVersion--}
```
public final DataMatrixVersion getDataMatrixVersion()
```


Λαμβάνει το μέγεθος συμβόλου του Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Λαμβάνει την κωδικοποίηση ECI. Χρησιμοποιείται όταν η EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1.

**Returns:**
int - κωδικοποίηση ECI.
### getEccType() {#getEccType--}
```
public final DataMatrixEccType getEccType()
```


Λαμβάνει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

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
### getRows() {#getRows--}
```
public final int getRows()
```


Αριθμός σειρών.

**Returns:**
int
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final int getStructuredAppendFileId()
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final DataMatrixVersion getVersion()
```


Λαμβάνει το μέγεθος συμβόλου του Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Returns:**
[DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) - a Datamatrix symbol size.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderProgramming() {#isReaderProgramming--}
```
public final boolean isReaderProgramming()
```


Χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. Προεπιλεγμένη τιμή: false.

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


Αριθμός στηλών.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setDataMatrixEcc(DataMatrixEccType value) {#setDataMatrixEcc-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setDataMatrixEcc(DataMatrixEccType value)
```


Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ένας τύπος ECC του Datamatrix. |

### setDataMatrixEncodeMode(DataMatrixEncodeMode value) {#setDataMatrixEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setDataMatrixEncodeMode(DataMatrixEncodeMode value)
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setDataMatrixVersion(DataMatrixVersion value) {#setDataMatrixVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setDataMatrixVersion(DataMatrixVersion value)
```


Ορίζει το μέγεθος συμβόλου του Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | ένα μέγεθος συμβόλου του Datamatrix. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν η EncodeMode είναι Auto. Προεπιλεγμένη τιμή: ISO-8859-1.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Κωδικοποίηση ECI. |

### setEccType(DataMatrixEccType value) {#setEccType-com.aspose.barcode.generation.DataMatrixEccType-}
```
public final void setEccType(DataMatrixEccType value)
```


Ορίζει έναν τύπο ECC του Datamatrix. Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEccType](../../com.aspose.barcode.generation/datamatrixecctype) | ένας τύπος ECC του Datamatrix. |

### setEncodeMode(DataMatrixEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public final void setEncodeMode(DataMatrixEncodeMode value)
```


Λειτουργία κωδικοποίησης του barcode Datamatrix. Προεπιλεγμένη τιμή: EncodeMode.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με DataMatrixEccType.Ecc200 ή DataMatrixEccType.EccAuto. Δεν μπορούν να χρησιμοποιηθούν με EncodeTypes.GS1DataMatrix. Προεπιλεγμένη τιμή: MacroCharacters.None.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setReaderProgramming(boolean value) {#setReaderProgramming-boolean-}
```
public final void setReaderProgramming(boolean value)
```


Χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. Προεπιλεγμένη τιμή: false.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Αριθμός σειρών.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setStructuredAppendFileId(int value) {#setStructuredAppendFileId-int-}
```
public final void setStructuredAppendFileId(int value)
```


Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix. Προεπιλεγμένη τιμή: 0.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVersion(DataMatrixVersion value) {#setVersion-com.aspose.barcode.generation.DataMatrixVersion-}
```
public final void setVersion(DataMatrixVersion value)
```


Ορίζει το μέγεθος συμβόλου του Datamatrix. Προεπιλεγμένη τιμή: Version.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [DataMatrixVersion](../../com.aspose.barcode.generation/datamatrixversion) | ένα μέγεθος συμβόλου του Datamatrix. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια ευανάγνωστη αναπαράσταση συμβολοσειράς αυτού του [DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters).

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


---
title: BaseEncodeType
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Base class for SymbologyEncodeType.
type: docs
weight: 16
url: /el/androidjava/com.aspose.barcode.generation/baseencodetype/
---
**Inheritance:**
java.lang.Object
```
public class BaseEncodeType
```

Base class for SymbologyEncodeType.
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή BaseEncodeType. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | Λαμβάνει μια ταξινόμηση αυτού του συμβολισμού. |
| [getString()](#getString--) | Μετατρέπει την περίπτωση BaseEncodeType στην ισοδύναμη αναπαράσταση συμβολοσειράς. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | Μετατρέπει την περίπτωση BaseEncodeType στην ισοδύναμη αναπαράσταση συμβολοσειράς. |
| [getTypeIndex()](#getTypeIndex--) | Λαμβάνει έναν δείκτη του τύπου κωδικοποίησης |
| [getTypeName()](#getTypeName--) | Λαμβάνει ένα όνομα του τύπου κωδικοποίησης |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς του ονόματος ενός BaseEncodeType στην περίπτωση του. |
| [toString()](#toString--) | Επιστρέφει το όνομα του δοσμένου BaseEncodeType ως συμβολοσειρά. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseEncodeType στην περίπτωση του. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseEncodeType στην περίπτωση του. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή BaseEncodeType.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| άλλο | java.lang.Object | Μια τιμή BaseEncodeType για σύγκριση με αυτή την περίπτωση. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


Λαμβάνει μια ταξινόμηση αυτού του συμβολισμού.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


Converts the instance of BaseEncodeType to its equivalent string representation. The string format is: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - A string representing the complete value of the encode type
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


Converts the instance of BaseEncodeType to its equivalent string representation. The string format is: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | The BaseEncodeType instance to convert |

**Returns:**
java.lang.String - A string representing the complete value of the given encode type
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


Λαμβάνει έναν δείκτη του τύπου κωδικοποίησης

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


Λαμβάνει ένα όνομα του τύπου κωδικοποίησης

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς του ονόματος ενός BaseEncodeType στην περίπτωση του.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| stringEncodeType | java.lang.String | A string containing the name of a BaseEncodeType to convert. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει το όνομα του δοσμένου BaseEncodeType ως συμβολοσειρά.

**Returns:**
java.lang.String - A string representing the name of the encode type
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | A string in the format as "Index:-1; Name:None" to convert. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | An actual SingleEncodeType returns, when conversion has completed successfully; |

otherwise it returns null. |

**Returns:**
boolean -  **true**  if s was converted successfully; otherwise,  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | A string in the format as "Index:-1; Name:None" to convert. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | An actual SingleEncodeType returns, when conversion has completed successfully; |

otherwise it returns null. |

**Returns:**
boolean -  **true**  if s was converted successfully; otherwise,  **false** .
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


---
title: BaseDecodeType
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Βασική κλάση για MultiDecodeType και SingleDecodeType.
type: docs
weight: 23
url: /el/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

Βασική κλάση για MultiDecodeType και SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Καθορίζει εάν κάποιο από τους δοθέντες τύπους αποκωδικοποίησης περιλαμβάνεται στο |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [equals(Object other)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


Καθορίζει εάν κάποιο από τους δοθέντες τύπους αποκωδικοποίησης περιλαμβάνεται στο

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Τύποι προς επαλήθευση. |

**Returns:**
boolean - Η τιμή είναι true εάν κάποιοι τύποι περιλαμβάνονται στο.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| άλλο | com.aspose.barcode.barcoderecognition.MultiDecodeType | Τιμή java.lang.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean - True εάν το obj έχει την ίδια τιμή με αυτή την παρουσία· διαφορετικά, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Τιμή java.lang.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean - True εάν το obj έχει την ίδια τιμή με αυτή την παρουσία· διαφορετικά, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) value.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| άλλο | java.lang.Object | Τιμή java.lang.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean - True εάν το obj έχει την ίδια τιμή με αυτή την παρουσία· διαφορετικά, false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην αντίστοιχη παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - Επιστρέφεται ένα πραγματικό MultiDecodeType όταν η μετατροπή ολοκληρωθεί επιτυχώς·

διαφορετικά επιστρέφει αόριστο τύπο. ή MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην αντίστοιχη παρουσία του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή \"EAN8\" ή \"EAN13\" ή \"CodaBar\"... για μετατροπή. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή SingleDecodeType (-1, \"None\").
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


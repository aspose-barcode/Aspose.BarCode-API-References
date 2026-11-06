---
title: "MultiDecodeType"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Σύνθετος τύπος αποκωδικοποίησης."
type: docs
weight: 35
url: /el/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

Σύνθετος τύπος αποκωδικοποίησης.

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε σύνθετους τύπους MultiDecode που συνδυάζουν SingleDecodeType και τύπους MultiDecode.

```

```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Προσθέτει έναν ακόμη [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) στο MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Ελέγξτε αν αυτό περιέχει όλους τους τύπους από τους τύπους barcode. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | Περιέχει κάποιον από τους τύπους |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η συλλογή τύπων αποκωδικοποίησης περιέχει μόνο την καθορισμένη τιμή [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | Εξαιρεί το [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) από το MultiDecodeType και επιστρέφει νέα παρουσία MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | Αναπαριστά μια λίστα με μεμονωμένους τύπους. |
| [getSingleTypesCount()](#getSingleTypesCount--) | Επιστρέφει έναν αριθμό μεμονωμένων τύπων. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Υπερκαλυπτόμενη μέθοδος που αναπαριστά το MultiDecodeType ως συμβολοσειρά. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην παρουσία του, αφού έχει προσδιοριστεί ο συγκεκριμένος τύπος. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην παρουσία του. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην παρουσία του. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Πίνακας μεμονωμένων τύπων αποκωδικοποίησης |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Πίνακας πολλαπλών και μεμονωμένων τύπων αποκωδικοποίησης |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


Προσθέτει έναν ακόμη [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) στο MultiDecodeType.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ένας Single DecodeType που θα προστεθεί στη λίστα |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


Ελέγξτε αν αυτό περιέχει όλους τους τύπους από τους τύπους barcode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Είσοδος μεμονωμένων ή πολλαπλών τύπων barcode |

**Returns:**
boolean - Η τιμή είναι true εάν όλοι οι τύποι περιλαμβάνονται στο
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


Περιέχει κάποιον από τους τύπους

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | Τύποι αποκωδικοποίησης |

**Returns:**
boolean - Η τιμή είναι true εάν περιλαμβάνονται κάποιοι τύποι
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | Μια τιμή [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η συλλογή τύπων αποκωδικοποίησης περιέχει μόνο την καθορισμένη τιμή [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Μια τιμή [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) για σύγκριση με αυτή τη συλλογή τύπων αποκωδικοποίησης. |

**Returns:**
boolean -  **true**  εάν αυτή η συλλογή περιέχει μόνο τον καθορισμένο τύπο αποκωδικοποίησης· διαφορετικά,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτό το αντικείμενο. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


Εξαιρεί το [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) από το MultiDecodeType και επιστρέφει νέα παρουσία MultiDecodeType.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | Ένας Single DecodeType που θα εξαλειφθεί. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


Αναπαριστά μια λίστα με μεμονωμένους τύπους.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - Λίστα μεμονωμένων τύπων
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


Επιστρέφει έναν αριθμό μεμονωμένων τύπων.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
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


Υπερκαλυπτόμενη μέθοδος που αναπαριστά το MultiDecodeType ως συμβολοσειρά.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει την παρουσία MultiDecodeType ως "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός BaseDecodeType στην περίπτωση του, αφού καθοριστεί ο συγκεκριμένος τύπος. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός MultiDecodeType στην περίπτωση του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Μια συμβολοσειρά που περιέχει μια αναπαράσταση MultiDecodeType για μετατροπή. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


Μετατρέπει την αναπαράσταση συμβολοσειράς ενός SingleDecodeType στην περίπτωση του. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| parsingType | java.lang.String | Μια συμβολοσειρά που περιέχει ένα SingleDecodeType στη μορφή "EAN8" ή "EAN13" ή "CodaBar"... για μετατροπή. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

διαφορετικά επιστρέφει αόριστο τύπο. ή SingleDecodeType (-1, "None").
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


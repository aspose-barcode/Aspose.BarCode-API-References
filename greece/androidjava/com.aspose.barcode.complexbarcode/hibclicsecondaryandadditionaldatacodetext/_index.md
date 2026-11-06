---
title: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC LIC που αποθηκεύει δευτερεύοντα δεδομένα."
type: docs
weight: 17
url: /el/androidjava/com.aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICSecondaryAndAdditionalDataCodetext extends HIBCLICComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC LIC που αποθηκεύει δευτερεύοντα δεδομένα.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext()](#HIBCLICSecondaryAndAdditionalDataCodetext--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  HIBCLICSecondaryAndAdditionalDataCodetext . |
| [getBarcodeType()](#getBarcodeType--) | Αποκτά ή ορίζει τον τύπο του barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί codetext |
| [getData()](#getData--) | Αναγνωρίζει δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα. |
| [getLinkCharacter()](#getLinkCharacter--) | Αναγνωρίζει χαρακτήρα συνδέσμου. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί την παρουσία από το κατασκευασμένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Αποκτά ή ορίζει τον τύπο του barcode. |
| [setData(SecondaryAndAdditionalData value)](#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | Αναγνωρίζει δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | Αναγνωρίζει χαρακτήρα συνδέσμου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICSecondaryAndAdditionalDataCodetext() {#HIBCLICSecondaryAndAdditionalDataCodetext--}
```
public HIBCLICSecondaryAndAdditionalDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  HIBCLICSecondaryAndAdditionalDataCodetext .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια  HIBCLICSecondaryAndAdditionalDataCodetext  τιμή για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Λαμβάνει ή ορίζει τον τύπο barcode. HIBC LIC codetext μπορεί να κωδικοποιηθεί χρησιμοποιώντας HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC τύπους κωδικοποίησης. Προεπιλεγμένη τιμή: HIBCCode39LIC.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Δημιουργεί codetext

**Returns:**
java.lang.String - Κατασκευασμένο codetext
### getData() {#getData--}
```
public SecondaryAndAdditionalData getData()
```


Αναγνωρίζει δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### getLinkCharacter() {#getLinkCharacter--}
```
public char getLinkCharacter()
```


Αναγνωρίζει χαρακτήρα συνδέσμου.

**Returns:**
char
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Αρχικοποιεί την παρουσία από το κατασκευασμένο codetext.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Κατασκευασμένο codetext. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


Λαμβάνει ή ορίζει τον τύπο barcode. HIBC LIC codetext μπορεί να κωδικοποιηθεί χρησιμοποιώντας HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC και HIBCQRLIC τύπους κωδικοποίησης. Προεπιλεγμένη τιμή: HIBCCode39LIC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(SecondaryAndAdditionalData value) {#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setData(SecondaryAndAdditionalData value)
```


Αναγνωρίζει δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public void setLinkCharacter(char value)
```


Αναγνωρίζει χαρακτήρα συνδέσμου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | char |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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


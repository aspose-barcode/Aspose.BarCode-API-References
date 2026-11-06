---
title: "HIBCPASCodetext"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS."
type: docs
weight: 18
url: /el/androidjava/com.aspose.barcode.complexbarcode/hibcpascodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class HIBCPASCodetext implements IComplexCodetext
```

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου ενσωματωμένου στον κώδικα HIBC PAS.

--------------------

> ```
> This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.
>   
> 
>   HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
>   complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
>   complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
>   complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
>   complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
>   ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext);
>   BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.HIBC_DATA_MATRIX_PAS);
>   reader.readBarCodes();
>   String codetext = reader.getFoundBarCodes()[0].getCodeText();
>  	HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
>   System.out.println("Data location: {0}", readCodetext.getDataLocation());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[0].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[0].getData());
>   System.out.print("Data type: {0}. ", readCodetext.getRecords()[1].getDataType());
>   System.out.println("Data: {0}", readCodetext.getRecords()[1].getData());
>       }
>   }
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HIBCPASCodetext()](#HIBCPASCodetext--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addRecord(HIBCPASRecord record)](#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-) | Προσθέτει νέα εγγραφή |
| [addRecord(int dataType, String data)](#addRecord-int-java.lang.String-) | Προσθέτει νέα εγγραφή |
| [clear()](#clear--) | Καθαρίζει τη λίστα εγγραφών |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή HIBCPASCodetext. |
| [getBarcodeType()](#getBarcodeType--) | Λαμβάνει τον τύπο barcode. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Δημιουργεί codetext |
| [getDataLocation()](#getDataLocation--) | Καθορίζει τη θέση των δεδομένων. |
| [getRecords()](#getRecords--) | Λαμβάνει τη λίστα εγγραφών |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Αρχικοποιεί την παρουσία από το κατασκευασμένο codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | Αποκτά ή ορίζει τον τύπο του barcode. |
| [setDataLocation(int value)](#setDataLocation-int-) | Καθορίζει τη θέση των δεδομένων. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCPASCodetext() {#HIBCPASCodetext--}
```
public HIBCPASCodetext()
```


### addRecord(HIBCPASRecord record) {#addRecord-com.aspose.barcode.complexbarcode.HIBCPASRecord-}
```
public void addRecord(HIBCPASRecord record)
```


Προσθέτει νέα εγγραφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| record | [HIBCPASRecord](../../com.aspose.barcode.complexbarcode/hibcpasrecord) | Εγγραφή προς προσθήκη |

### addRecord(int dataType, String data) {#addRecord-int-java.lang.String-}
```
public void addRecord(int dataType, String data)
```


Προσθέτει νέα εγγραφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dataType | int | Τύπος δεδομένων |
| δεδομένα | java.lang.String | Συμβολοσειρά δεδομένων |

### clear() {#clear--}
```
public void clear()
```


Καθαρίζει τη λίστα εγγραφών

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή HIBCPASCodetext.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια  HIBCPASCodetext  τιμή για σύγκριση με αυτήν την περίπτωση. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


Λαμβάνει τον τύπο barcode.

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
### getDataLocation() {#getDataLocation--}
```
public int getDataLocation()
```


Καθορίζει τη θέση των δεδομένων.

**Returns:**
int
### getRecords() {#getRecords--}
```
public System.Collections.Generic.List<HIBCPASRecord> getRecords()
```


Λαμβάνει τη λίστα εγγραφών

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.barcode.complexbarcode.HIBCPASRecord> - Λίστα εγγραφών
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


Λαμβάνει ή ορίζει τον τύπο barcode. Το HIBC PAS codetext μπορεί να κωδικοποιηθεί χρησιμοποιώντας τους τύπους κωδικοποίησης HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS και HIBCQRPAS. Προεπιλεγμένη τιμή: HIBCCode39PAS.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setDataLocation(int value) {#setDataLocation-int-}
```
public void setDataLocation(int value)
```


Καθορίζει τη θέση των δεδομένων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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


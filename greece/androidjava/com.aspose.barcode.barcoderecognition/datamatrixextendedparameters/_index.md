---
title: DataMatrixExtendedParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Αποθηκεύει ειδικά δεδομένα του barcode DataMatrix που αναγνωρίστηκε
type: docs
weight: 31
url: /el/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει ειδικά δεδομένα του barcode DataMatrix που αναγνωρίστηκε

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη  DataMatrixExtendedParameters  τιμή. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Λαμβάνει το ID του barcode λειτουργίας structured append του DataMatrix. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Λαμβάνει τον αριθμό των barcode σε λειτουργία δομημένης προσάρτησης DataMatrix. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Λαμβάνει το ID του barcode λειτουργίας structured append του DataMatrix. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [isReaderProgramming()](#isReaderProgramming--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του DataMatrixExtendedParameters είναι ίση με τη δεύτερη. |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του DataMatrixExtendedParameters διαφέρει από τη δεύτερη. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DataMatrixExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη  DataMatrixExtendedParameters  τιμή.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Λαμβάνει το ID του barcode σε λειτουργία δομημένης προσάρτησης DataMatrix. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Το ID του barcode σε λειτουργία δομημένης προσάρτησης DataMatrix.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Λαμβάνει τον αριθμό των barcode σε λειτουργία δομημένης προσάρτησης DataMatrix. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

Τιμή: Ο αριθμός των barcode σε λειτουργία δομημένης προσάρτησης DataMatrix.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


Λαμβάνει το ID του barcode σε λειτουργία δομημένης προσάρτησης DataMatrix. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Το ID του barcode σε λειτουργία δομημένης προσάρτησης DataMatrix.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές

Τιμή: Επιστρέφει  **true**  εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές· διαφορετικά,  **false** .

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
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




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του DataMatrixExtendedParameters είναι ίση με τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει την ίδια τιμή με τη δεύτερη· διαφορετικά,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του DataMatrixExtendedParameters διαφέρει από τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει διαφορετική τιμή από τη δεύτερη· διαφορετικά,  **false** .
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του DataMatrixExtendedParameters.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το DataMatrixExtendedParameters.
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


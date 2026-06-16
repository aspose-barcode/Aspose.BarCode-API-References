---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Αποθηκεύει ειδικά δεδομένα του barcode DotCode που αναγνωρίστηκε
type: docs
weight: 33
url: /el/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει ειδικά δεδομένα του barcode DotCode που αναγνωρίστηκε

Αυτό το παράδειγμα δείχνει πώς να λάβετε τις ακατέργαστες τιμές DotCode.

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Λαμβάνει το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Λαμβάνει τον αριθμό των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Λαμβάνει το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Λαμβάνει τον αριθμό των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [isReaderInitialization()](#isReaderInitialization--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) είναι ίση με τη δεύτερη. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) διαφέρει από τη δεύτερη. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

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
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


Δείχνει εάν ο κώδικας χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη γραμμωτού κώδικα. Η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Λαμβάνει το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των γραμμωτών κωδίκων. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.

**Returns:**
int - το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Λαμβάνει τον αριθμό των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

Τιμή: Ο αριθμός των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.

**Returns:**
int - ο αριθμός των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Λαμβάνει το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των γραμμωτών κωδίκων. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.

**Returns:**
int - το ID του γραμμωτού κώδικα DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Λαμβάνει τον αριθμό των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών. Η προεπιλεγμένη τιμή είναι -1. Ο αριθμός πρέπει να είναι τιμή από 1 έως 35.

Τιμή: Ο αριθμός των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.

**Returns:**
int - ο αριθμός των γραμμωτών κωδίκων DotCode σε λειτουργία προσάρτησης δομημένων κωδικών.
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




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) είναι ίση με τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει την ίδια τιμή με τη δεύτερη· διαφορετικά,  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν η πρώτη τιμή του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) διαφέρει από τη δεύτερη.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Μια πρώτη τιμή σύγκρισης |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Μια δεύτερη τιμή σύγκρισης |

**Returns:**
boolean -  **true**  εάν η πρώτη έχει διαφορετική τιμή από τη δεύτερη· διαφορετικά,  **false** .
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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


---
title: "AztecExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec"
type: docs
weight: 12
url: /el/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει ειδικά δεδομένα του αναγνωρισμένου barcode Aztec

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("test.png");
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή AztecExtendedParameters. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Λαμβάνει το ID του barcode λειτουργίας δομημένης προσθήκης Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Λαμβάνει τον αριθμό των barcode λειτουργίας δομημένης προσθήκης Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Λαμβάνει το ID αρχείου της λειτουργίας δομημένης προσθήκης Aztec. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές. |
| [isReaderInitialization()](#isReaderInitialization--) | Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του AztecExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή AztecExtendedParameters.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτό το αντικείμενο. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
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


Λαμβάνει το ID του barcode λειτουργίας δομημένης προσθήκης Aztec. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι 0.

Τιμή: Το ID του barcode της λειτουργίας δομημένης προσθήκης Aztec.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Λαμβάνει τον αριθμό των barcode της λειτουργίας δομημένης προσθήκης Aztec. Η προεπιλεγμένη τιμή είναι 0. Ο αριθμός πρέπει να είναι τιμή από 1 έως 26.

Τιμή: Ο αριθμός των barcode της λειτουργίας δομημένης προσθήκης Aztec.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Λαμβάνει το ID αρχείου της λειτουργίας δομημένης προσθήκης Aztec. Η προεπιλεγμένη τιμή είναι κενή συμβολοσειρά.

Τιμή: Το ID αρχείου της λειτουργίας δομημένης προσθήκης Aztec.

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές.

Τιμή: Επιστρέφει  **true**  εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές· διαφορετικά,  **false** .

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Δείχνει εάν ο κώδικας χρησιμοποιείται για να υποδείξει στον αναγνώστη να ερμηνεύσει τα παρακάτω δεδομένα ως οδηγίες για την εκκίνηση ή την επαναπρογραμματισμό του αναγνώστη barcode. Η προεπιλεγμένη τιμή είναι false.

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




### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του AztecExtendedParameters.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το AztecExtendedParameters.
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


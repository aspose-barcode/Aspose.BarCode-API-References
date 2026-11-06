---
title: "Pdf417ExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode"
type: docs
weight: 38
url: /el/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

Αποθηκεύει μεταδεδομένα MacroPdf417 του αναγνωρισμένου barcode

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  Pdf417ExtendedParameters . |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Όνομα παραλήπτη Macro PDF417 (προαιρετικό). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Άθροισμα ελέγχου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Αποκτά το αναγνωριστικό αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Όνομα αρχείου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Μέγεθος αρχείου Macro PDF417 (προαιρετικό). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Αποκτά το αναγνωριστικό τμήματος του barcode, διαθέσιμο μόνο με MacroPdf417. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Αποκτά τον αριθμό τμημάτων του macro pdf417 barcode. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Όνομα αποστολέα Macro PDF417 (προαιρετικό). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Δείχνει εάν το τμήμα είναι το τελευταίο τμήμα ενός αρχείου Macro PDF417. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Χρονική σήμανση Macro PDF417 (προαιρετικό). |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [isCode128Emulation()](#isCode128Emulation--) | Σημαία που υποδεικνύει ότι ο κώδικας MicroPdf417 κωδικοποιήθηκε με τις λέξεις κώδικα 908, 909, 910 ή 911 προσομοίωσης Code 128. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές. |
| [isLinked()](#isLinked--) | Σημαία που υποδεικνύει ότι ο barcode πρέπει να συνδεθεί με 1D barcode. |
| [isReaderInitialization()](#isReaderInitialization--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Pdf417ExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  Pdf417ExtendedParameters .

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
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Όνομα παραλήπτη Macro PDF417 (προαιρετικό).

**Returns:**
java.lang.String - Όνομα παραλήπτη.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Άθροισμα ελέγχου Macro PDF417 (προαιρετικό).

**Returns:**
int - Άθροισμα ελέγχου.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


Αποκτά το αναγνωριστικό αρχείου του barcode, διαθέσιμο μόνο με MacroPdf417.

Τιμή: Το αναγνωριστικό αρχείου για MacroPdf417

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Όνομα αρχείου Macro PDF417 (προαιρετικό).

**Returns:**
java.lang.String - Όνομα αρχείου.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Μέγεθος αρχείου Macro PDF417 (προαιρετικό).

**Returns:**
int - Μέγεθος αρχείου.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


Αποκτά το αναγνωριστικό τμήματος του barcode, διαθέσιμο μόνο με MacroPdf417.

Τιμή: Το αναγνωριστικό τμήματος του barcode.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


Λαμβάνει τον αριθμό τμημάτων του macro pdf417 barcode. Η προεπιλεγμένη τιμή είναι -1.

Τιμή: Αριθμός τμημάτων.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Όνομα αποστολέα Macro PDF417 (προαιρετικό).

**Returns:**
java.lang.String - Όνομα αποστολέα
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


Δείχνει εάν το τμήμα είναι το τελευταίο τμήμα ενός αρχείου Macro PDF417.

**Returns:**
boolean - Τερματιστής.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Χρονική σήμανση Macro PDF417 (προαιρετικό).

**Returns:**
java.time.LocalDateTime - Χρονοσφραγίδα.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


Σημαία που υποδεικνύει ότι ο κώδικας MicroPdf417 κωδικοποιήθηκε με τις λέξεις κώδικα 908, 909, 910 ή 911 προσομοίωσης Code 128.

**Returns:**
boolean - Σημαία προσομοίωσης Code 128
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές.

Τιμή: Επιστρέφει  **true**  εάν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές· διαφορετικά,  **false** .

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


Σημαία που υποδεικνύει ότι ο barcode πρέπει να συνδεθεί με 1D barcode.

Τιμή: Σημαία σύνδεσης

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη.

Τιμή: Σημαία αρχικοποίησης αναγνώστη

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


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Pdf417ExtendedParameters.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το Pdf417ExtendedParameters.
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


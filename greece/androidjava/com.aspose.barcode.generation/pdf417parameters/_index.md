---
title: Pdf417Parameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Παράμετροι PDF417.
type: docs
weight: 60
url: /el/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

Παράμετροι PDF417. Περιέχει παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία Structured Append (ίδια με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις μη συνδεδεμένες λειτουργίες UCC/EAN-128 σε GS1MicroPdf417.

```

 [C#]
 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Αριθμός στηλών. |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. |
| [getErrorLevel()](#getErrorLevel--) | Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα. |
| [getMacroCharacters()](#getMacroCharacters--) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός λέξης 922) στο τμήμα. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 barcode χρονική σήμανση (προαιρετικό πεδίο). |
| [getPdf417CompactionMode()](#getPdf417CompactionMode--) | Pdf417 τύπος συμβολισμού για τη λειτουργία συμπίεσης του BarCode. |
| [getPdf417ECIEncoding()](#getPdf417ECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417EncodeMode()](#getPdf417EncodeMode--) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. |
| [getPdf417ErrorLevel()](#getPdf417ErrorLevel--) | Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα. |
| [getPdf417MacroAddressee()](#getPdf417MacroAddressee--) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getPdf417MacroChecksum()](#getPdf417MacroChecksum--) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getPdf417MacroECIEncoding()](#getPdf417MacroECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getPdf417MacroFileID()](#getPdf417MacroFileID--) | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο). |
| [getPdf417MacroFileName()](#getPdf417MacroFileName--) | MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). |
| [getPdf417MacroFileSize()](#getPdf417MacroFileSize--) | MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). |
| [getPdf417MacroSegmentID()](#getPdf417MacroSegmentID--) | MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getPdf417MacroSegmentsCount--) | MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). |
| [getPdf417MacroSender()](#getPdf417MacroSender--) | MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). |
| [getPdf417MacroTerminator()](#getPdf417MacroTerminator--) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός λέξης 922) στο τμήμα. |
| [getPdf417MacroTimeStamp()](#getPdf417MacroTimeStamp--) | MacroPdf417 barcode χρονική σήμανση (προαιρετικό πεδίο). |
| [getPdf417Truncate()](#getPdf417Truncate--) | Είναι ο τύπος συμβολισμού Pdf417 του BarCode περικομμένος (για μείωση χώρου). |
| [getRows()](#getRows--) | Αριθμός σειρών. |
| [getTruncate()](#getTruncate--) | Είναι ο τύπος συμβολισμού Pdf417 του BarCode περικομμένος (για μείωση χώρου). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [isLinked()](#isLinked--) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [setColumns(int value)](#setColumns-int-) | Αριθμός στηλών. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα. |
| [setLinked(boolean value)](#setLinked-boolean-) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός λέξης 922) στο τμήμα. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 barcode χρονική σήμανση (προαιρετικό πεδίο). |
| [setPdf417CompactionMode(Pdf417CompactionMode value)](#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-) | Pdf417 τύπος συμβολισμού για τη λειτουργία συμπίεσης του BarCode. |
| [setPdf417ECIEncoding(int value)](#setPdf417ECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417EncodeMode(Pdf417EncodeMode value)](#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. |
| [setPdf417ErrorLevel(Pdf417ErrorLevel value)](#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα. |
| [setPdf417MacroAddressee(String value)](#setPdf417MacroAddressee-java.lang.String-) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setPdf417MacroChecksum(int value)](#setPdf417MacroChecksum-int-) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setPdf417MacroECIEncoding(int value)](#setPdf417MacroECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setPdf417MacroFileID(int value)](#setPdf417MacroFileID-int-) | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο). |
| [setPdf417MacroFileName(String value)](#setPdf417MacroFileName-java.lang.String-) | MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). |
| [setPdf417MacroFileSize(int value)](#setPdf417MacroFileSize-int-) | MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). |
| [setPdf417MacroSegmentID(int value)](#setPdf417MacroSegmentID-int-) | MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount(int value)](#setPdf417MacroSegmentsCount-int-) | MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). |
| [setPdf417MacroSender(String value)](#setPdf417MacroSender-java.lang.String-) | MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). |
| [setPdf417MacroTerminator(Pdf417MacroTerminator value)](#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός λέξης 922) στο τμήμα. |
| [setPdf417MacroTimeStamp(LocalDateTime value)](#setPdf417MacroTimeStamp-java.time.LocalDateTime-) | MacroPdf417 barcode χρονική σήμανση (προαιρετικό πεδίο). |
| [setPdf417Truncate(boolean value)](#setPdf417Truncate-boolean-) | Είναι ο τύπος συμβολισμού Pdf417 του BarCode περικομμένος (για μείωση χώρου). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [setRows(int value)](#setRows-int-) | Αριθμός σειρών. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Είναι ο τύπος συμβολισμού Pdf417 του BarCode περικομμένος (για μείωση χώρου). |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλου χαρακτήρων.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters στο MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 barcode όνομα παραλήπτη (προαιρετικό πεδίο). MicroPDF417 barcode όνομα παραλήπτη (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο). MicroPDF417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 barcode ID αρχείου (απαιτούμενο πεδίο). MicroPDF417 barcode ID αρχείου (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). MicroPDF417 μέγεθος αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. MicroPDF417 barcode ID τμήματος (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). MicroPDF417 barcode αριθμός τμημάτων (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αποστολέα (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν πρέπει να προσθέσει τον κωδικό τερματισμού Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417CompactionMode() {#getPdf417CompactionMode--}
```
public final Pdf417CompactionMode getPdf417CompactionMode()
```


Τύπος συμβολισμού Pdf417 για τη λειτουργία συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.Auto.

**Returns:**
[Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode)
### getPdf417ECIEncoding() {#getPdf417ECIEncoding--}
```
public final int getPdf417ECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλου χαρακτήρων.

**Returns:**
int
### getPdf417EncodeMode() {#getPdf417EncodeMode--}
```
public final Pdf417EncodeMode getPdf417EncodeMode()
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getPdf417ErrorLevel() {#getPdf417ErrorLevel--}
```
public final Pdf417ErrorLevel getPdf417ErrorLevel()
```


Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getPdf417MacroAddressee() {#getPdf417MacroAddressee--}
```
public final String getPdf417MacroAddressee()
```


MacroPdf417 barcode όνομα παραλήπτη (προαιρετικό πεδίο). MicroPDF417 barcode όνομα παραλήπτη (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroChecksum() {#getPdf417MacroChecksum--}
```
public final int getPdf417MacroChecksum()
```


MacroPdf417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο). MicroPDF417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

**Returns:**
int
### getPdf417MacroECIEncoding() {#getPdf417MacroECIEncoding--}
```
public final int getPdf417MacroECIEncoding()
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417.

**Returns:**
int
### getPdf417MacroFileID() {#getPdf417MacroFileID--}
```
public final int getPdf417MacroFileID()
```


MacroPdf417 barcode ID αρχείου (απαιτούμενο πεδίο). MicroPDF417 barcode ID αρχείου (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getPdf417MacroFileName() {#getPdf417MacroFileName--}
```
public final String getPdf417MacroFileName()
```


MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroFileSize() {#getPdf417MacroFileSize--}
```
public final int getPdf417MacroFileSize()
```


MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). MicroPDF417 μέγεθος αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Returns:**
int
### getPdf417MacroSegmentID() {#getPdf417MacroSegmentID--}
```
public final int getPdf417MacroSegmentID()
```


MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. MicroPDF417 barcode ID τμήματος (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getPdf417MacroSegmentsCount() {#getPdf417MacroSegmentsCount--}
```
public final int getPdf417MacroSegmentsCount()
```


MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). MicroPDF417 barcode αριθμός τμημάτων (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
int
### getPdf417MacroSender() {#getPdf417MacroSender--}
```
public final String getPdf417MacroSender()
```


MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αποστολέα (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getPdf417MacroTerminator() {#getPdf417MacroTerminator--}
```
public final Pdf417MacroTerminator getPdf417MacroTerminator()
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν πρέπει να προσθέσει τον κωδικό τερματισμού Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getPdf417MacroTimeStamp() {#getPdf417MacroTimeStamp--}
```
public final LocalDateTime getPdf417MacroTimeStamp()
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append).

**Returns:**
java.time.LocalDateTime
### getPdf417Truncate() {#getPdf417Truncate--}
```
public final boolean getPdf417Truncate()
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία.

**Returns:**
boolean
### getRows() {#getRows--}
```
public final int getRows()
```


Αριθμός σειρών.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτή. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως barcode Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 στο GS1MicroPdf417 και τη σημαία σύνδεσης (Linkage Flag) (918) στα barcodes MicroPdf417 και Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη.

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

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτή. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως barcode Code 128.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Αριθμός στηλών.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλου χαρακτήρων.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Τύπος συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 \\u201cLinked\\u201d λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 στο GS1MicroPdf417 και τη σημαία σύνδεσης (Linkage Flag) (918) στα barcodes MicroPdf417 και Pdf417.

```

 [C#]
 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes GS1 Linked modes 906, 907 with any AI
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsLinked = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
 
```

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None.

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters στο MicroPdf417.

```

 [C#]
 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
     using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
       foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
 generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText);
 
```

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 barcode όνομα παραλήπτη (προαιρετικό πεδίο). MicroPDF417 barcode όνομα παραλήπτη (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο). MicroPDF417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 barcode ID αρχείου (απαιτούμενο πεδίο). MicroPDF417 barcode ID αρχείου (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). MicroPDF417 μέγεθος αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. MicroPDF417 barcode ID τμήματος (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). MicroPDF417 barcode αριθμός τμημάτων (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αποστολέα (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν πρέπει να προσθέσει τον κωδικό τερματισμού Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDateTime |  |

### setPdf417CompactionMode(Pdf417CompactionMode value) {#setPdf417CompactionMode-com.aspose.barcode.generation.Pdf417CompactionMode-}
```
public final void setPdf417CompactionMode(Pdf417CompactionMode value)
```


Τύπος συμβολισμού Pdf417 για τη λειτουργία συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417CompactionMode](../../com.aspose.barcode.generation/pdf417compactionmode) |  |

### setPdf417ECIEncoding(int value) {#setPdf417ECIEncoding-int-}
```
public final void setPdf417ECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλου χαρακτήρων.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417EncodeMode(Pdf417EncodeMode value) {#setPdf417EncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setPdf417EncodeMode(Pdf417EncodeMode value)
```


Αναγνωρίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setPdf417ErrorLevel(Pdf417ErrorLevel value) {#setPdf417ErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setPdf417ErrorLevel(Pdf417ErrorLevel value)
```


Ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Τύπος συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα. |

### setPdf417MacroAddressee(String value) {#setPdf417MacroAddressee-java.lang.String-}
```
public final void setPdf417MacroAddressee(String value)
```


MacroPdf417 barcode όνομα παραλήπτη (προαιρετικό πεδίο). MicroPDF417 barcode όνομα παραλήπτη (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPdf417MacroChecksum(int value) {#setPdf417MacroChecksum-int-}
```
public final void setPdf417MacroChecksum(int value)
```


MacroPdf417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο). MicroPDF417 barcode άθροισμα ελέγχου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroECIEncoding(int value) {#setPdf417MacroECIEncoding-int-}
```
public final void setPdf417MacroECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroFileID(int value) {#setPdf417MacroFileID-int-}
```
public final void setPdf417MacroFileID(int value)
```


MacroPdf417 barcode ID αρχείου (απαιτούμενο πεδίο). MicroPDF417 barcode ID αρχείου (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroFileName(String value) {#setPdf417MacroFileName-java.lang.String-}
```
public final void setPdf417MacroFileName(String value)
```


MacroPdf417 barcode όνομα αρχείου (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPdf417MacroFileSize(int value) {#setPdf417MacroFileSize-int-}
```
public final void setPdf417MacroFileSize(int value)
```


MacroPdf417 μέγεθος αρχείου (προαιρετικό πεδίο). MicroPDF417 μέγεθος αρχείου (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroSegmentID(int value) {#setPdf417MacroSegmentID-int-}
```
public final void setPdf417MacroSegmentID(int value)
```


MacroPdf417 barcode ID τμήματος (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. MicroPDF417 barcode ID τμήματος (απαιτούμενο πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroSegmentsCount(int value) {#setPdf417MacroSegmentsCount-int-}
```
public final void setPdf417MacroSegmentsCount(int value)
```


MacroPdf417 barcode αριθμός τμημάτων (προαιρετικό πεδίο). MicroPDF417 barcode αριθμός τμημάτων (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setPdf417MacroSender(String value) {#setPdf417MacroSender-java.lang.String-}
```
public final void setPdf417MacroSender(String value)
```


MacroPdf417 barcode όνομα αποστολέα (προαιρετικό πεδίο). MicroPDF417 barcode όνομα αποστολέα (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setPdf417MacroTerminator(Pdf417MacroTerminator value) {#setPdf417MacroTerminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setPdf417MacroTerminator(Pdf417MacroTerminator value)
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν πρέπει να προσθέσει τον κωδικό τερματισμού Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setPdf417MacroTimeStamp(LocalDateTime value) {#setPdf417MacroTimeStamp-java.time.LocalDateTime-}
```
public final void setPdf417MacroTimeStamp(LocalDateTime value)
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append).

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDateTime |  |

### setPdf417Truncate(boolean value) {#setPdf417Truncate-boolean-}
```
public final void setPdf417Truncate(boolean value)
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη.

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

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters).
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


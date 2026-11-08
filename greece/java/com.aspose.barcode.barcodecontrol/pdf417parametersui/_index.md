---
title: "Pdf417ParametersUI"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Περιτύλιγμα UI για την κλάση com.aspose.barcode.generation.Pdf417Parameters."
type: docs
weight: 16
url: /el/java/com.aspose.barcode.barcodecontrol/pdf417parametersui/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417ParametersUI
```

Περιτύλιγμα UI για την κλάση com.aspose.barcode.generation.Pdf417Parameters.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Αριθμός στηλών. |
| [getECIEncoding()](#getECIEncoding--) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [getEncodeMode()](#getEncodeMode--) | Τύπος συμβολισμού Pdf417 της λειτουργίας κωδικοποίησης του BarCode. |
| [getErrorLevel()](#getErrorLevel--) | Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων η οποία οδηγεί σε μεγαλύτερη εικόνα. |
| [getMacroCharacters()](#getMacroCharacters--) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | Λαμβάνει το αναγνωριστικό αρχείου του macro barcode Pdf417. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Όνομα αρχείου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | Λαμβάνει το αναγνωριστικό τμήματος του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | Λαμβάνει τον αριθμό τμημάτων του macro barcode Pdf417. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Χρονική σήμανση του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [getRows()](#getRows--) | Αριθμός γραμμών. |
| [getTruncate()](#getTruncate--) | Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [isLinked()](#isLinked--) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 «Linked» λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [isReaderInitialization()](#isReaderInitialization--) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Αναλογία Ύψος/Πλάτος του μονάδας 2D BarCode. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [setColumns(int value)](#setColumns-int-) | Αριθμός στηλών. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Τύπος συμβολισμού Pdf417 της λειτουργίας κωδικοποίησης του BarCode. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | Ορίζει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων η οποία οδηγεί σε μεγαλύτερη εικόνα. |
| [setLinked(boolean value)](#setLinked-boolean-) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 «Linked» λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | Οι τιμές των Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | Άθροισμα ελέγχου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | Ορίζει το αναγνωριστικό αρχείου του macro barcode Pdf417. |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | Όνομα αρχείου του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | Ορίζει το αναγνωριστικό τμήματος του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | Ορίζει το macro Pdf417 barcode segments count. |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | Χρονική σήμανση του barcode MacroPdf417 (προαιρετικό πεδίο). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [setRows(int value)](#setRows-int-) | Αριθμός γραμμών. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιούνται για να ενημερώσουν τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζονται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Τύπος συμβολισμού Pdf417 της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: Pdf417EncodeMode.Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων η οποία οδηγεί σε μεγαλύτερη εικόνα.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για να επιτύχουν πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None.

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη του barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


Άθροισμα ελέγχου barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16‑bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

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


Αποκτά το αναγνωριστικό αρχείου του macro Pdf417 barcode. Χρησιμοποιείται για MacroPdf417.

**Returns:**
int - αναγνωριστικό αρχείου του macro Pdf417 barcode.
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


Λαμβάνει το αναγνωριστικό τμήματος του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1.

**Returns:**
int - αναγνωριστικό τμήματος του macro Pdf417 barcode, που ξεκινά από 0 έως MacroSegmentsCount - 1.
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


Λαμβάνει τον αριθμό τμημάτων του macro barcode Pdf417.

**Returns:**
int - αριθμός τμημάτων του macro Pdf417 barcode.
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα του barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


Αριθμός γραμμών.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου).

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


Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 «Linked» λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC.

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


Αριθμός στηλών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιούνται για να ενημερώσουν τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζονται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Τύπος συμβολισμού Pdf417 της λειτουργίας κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: Pdf417EncodeMode.Auto.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


Ορίζει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8, level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων η οποία οδηγεί σε μεγαλύτερη εικόνα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | Τύπος συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων που οδηγεί σε μεγαλύτερη εικόνα. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί 906, 907, 912, 913, 914, 915 «Linked» λειτουργίες UCC/EAN-128. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για να επιτύχουν πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη του barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


Άθροισμα ελέγχου barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16‑bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


Ορίζει το αναγνωριστικό αρχείου του macro Pdf417 barcode. Χρησιμοποιείται για MacroPdf417.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | αναγνωριστικό αρχείου του macro Pdf417 barcode. |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


Ορίζει το αναγνωριστικό τμήματος του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | αναγνωριστικό τμήματος του macro Pdf417 barcode, που ξεκινά από 0 έως MacroSegmentsCount - 1. |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


Ορίζει το macro Pdf417 barcode segments count.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | αριθμός τμημάτων του macro Pdf417 barcode. |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα του barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


Χρησιμοποιείται για να οδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


Αριθμός γραμμών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
public final native void wait(long arg0)
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


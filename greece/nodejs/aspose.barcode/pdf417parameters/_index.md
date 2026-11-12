---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι PDF417."
type: docs
weight: 770
url: /el/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

Παράμετροι PDF417. Περιλαμβάνει παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία δομημένης προσθήκης (ίδιο με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε λειτουργίες UCC/EAN-128 μη συνδεδεμένες (non Linked) στο GS1MicroPdf417

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [getColumns()](#getcolumns) | Αριθμός στηλών. |
| [getECIEncoding()](#geteciencoding) | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [getEncodeMode()](#getencodemode) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [getErrorLevel()](#geterrorlevel) | Αποκτά τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, το level0 σημαίνει χωρίς διόρθωση σφαλμάτων |
| [getMacroCharacters()](#getmacrocharacters) | Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με Micro |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 barcode addressee name (προαιρετικό πεδίο). MicroPDF417 barcode addressee name (προαιρετικό πεδίο για Structured A |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 barcode checksum (προαιρετικό πεδίο). MicroPDF417 barcode checksum (προαιρετικό πεδίο για Structured Append mode) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 barcode's file ID (Απαιτούμενο πεδίο). MicroPDF417 barcode's file ID (Απαιτούμενο πεδίο για Structured Append mode |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 barcode file name (προαιρετικό πεδίο). MicroPDF417 barcode file name (προαιρετικό πεδίο για Structured Append mode |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 file size (προαιρετικό πεδίο). MicroPDF417 file size (προαιρετικό πεδίο για Structured Append mode) Το μέγεθος αρχείου |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 barcode's segment ID (Απαιτούμενο πεδίο), που ξεκινά από 0, έως MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 barcode segments count (προαιρετικό πεδίο). MicroPDF417 barcode segments count (προαιρετικό πεδίο για Structured A |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 barcode sender name (προαιρετικό πεδίο). MicroPDF417 barcode sender name (προαιρετικό πεδίο για Structured Append |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PD. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 barcode time stamp (προαιρετικό πεδίο). MicroPDF417 barcode time stamp (προαιρετικό πεδίο για Structured Append mo |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | Τύπος συμβολισμού Pdf417 της λειτουργίας συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | Αποκτά τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, το level0 σημαίνει χωρίς διόρθωση σφαλμάτων |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode addressee name. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode checksum. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode's file ID. Χρησιμοποιείται για MacroPdf417. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode file name. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 file size. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode's segment ID, που ξεκινά από 0, έως MacroSegmentsCount - 1. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode segments count. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode sender name. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PD. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | Λαμβάνει macro Pdf417 barcode time stamp. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). |
| [getRows()](#getrows) | Αριθμός γραμμών. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [getTruncate()](#gettruncate) | Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). Επίσης γνωστό ως CompactPDF417. Δείκτης δεξιάς σειράς |
| [isCode128Emulation()](#iscode128emulation) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση λειτουργίες 908 και |
| [isLinked()](#islinked) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολή GS1MicroPdf417 κωδικοποιούνται 906, 907. |
| [isReaderInitialization()](#isreaderinitialization) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [setAspectRatio()](#setaspectratio) | Λόγος ύψους/πλάτους του μονάδας 2D BarCode. |
| [setCode128Emulation()](#setcode128emulation) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση λειτουργίες 908 και |
| [setColumns()](#setcolumns) | Αριθμός στηλών. |
| [setECIEncoding()](#seteciencoding) | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [setEncodeMode()](#setencodemode) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Ορίζει τον τύπο συμβολής Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, όπου level0 σημαίνει χωρίς διόρθωση σφαλμάτων. |
| [setLinked()](#setlinked) | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολή GS1MicroPdf417 κωδικοποιούνται 906, 907. |
| [setMacroCharacters()](#setmacrocharacters) | Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με Micro |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 barcode addressee name (προαιρετικό πεδίο). MicroPDF417 barcode addressee name (προαιρετικό πεδίο για Structured A |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 barcode checksum (προαιρετικό πεδίο). MicroPDF417 barcode checksum (προαιρετικό πεδίο για Structured Append mode) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 barcode's file ID (Απαιτούμενο πεδίο). MicroPDF417 barcode's file ID (Απαιτούμενο πεδίο για Structured Append mode |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 barcode file name (προαιρετικό πεδίο). MicroPDF417 barcode file name (προαιρετικό πεδίο για Structured Append mode |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 file size (προαιρετικό πεδίο). MicroPDF417 file size (προαιρετικό πεδίο για Structured Append mode) Το μέγεθος αρχείου |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 barcode's segment ID (Απαιτούμενο πεδίο), που ξεκινά από 0, έως MacroSegmentsCount - 1. MicroPDF417 barcode's |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 barcode segments count (προαιρετικό πεδίο). MicroPDF417 barcode segments count (προαιρετικό πεδίο για Structured A |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 barcode sender name (προαιρετικό πεδίο). MicroPDF417 barcode sender name (προαιρετικό πεδίο για Structured Append |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PD. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 barcode time stamp (προαιρετικό πεδίο). MicroPDF417 barcode time stamp (προαιρετικό πεδίο για Structured Append mo |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | Τύπος συμβολισμού Pdf417 της λειτουργίας συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Αναγνωριστικά Εκτεταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Ορίζει τον τύπο συμβολής Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, όπου level0 σημαίνει χωρίς διόρθωση σφαλμάτων. |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | Ορίζει το όνομα παραλήπτη του macro barcode Pdf417. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | Ορίζει το άθροισμα ελέγχου (checksum) του macro barcode Pdf417. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | Ορίζει το αναγνωριστικό αρχείου (file ID) του macro barcode Pdf417. Χρησιμοποιείται για MacroPdf417. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | Ορίζει το όνομα αρχείου του macro barcode Pdf417. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | Ορίζει το μέγεθος αρχείου του macro Pdf417. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | Ορίζει το αναγνωριστικό τμήματος (segment ID) του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | Ορίζει τον αριθμό τμημάτων του macro barcode Pdf417. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | Ορίζει το όνομα αποστολέα του macro barcode Pdf417. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PD. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | Ορίζει τη χρονική σήμανση (time stamp) του macro barcode Pdf417. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). |
| [setReaderInitialization(value)](#setreaderinitialization) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| [setRows()](#setrows) | Αριθμός γραμμών. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Αναγνωρίζει το ID του barcode λειτουργίας δομημένης προσθήκης DotCode. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τα barcodes |
| [setTruncate()](#settruncate) | Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). Επίσης γνωστό ως CompactPDF417. Δείκτης δεξιάς σειράς |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Pdf417Parameters. |

### getAspectRatio() {#getaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### getColumns() {#getcolumns}

Αριθμός στηλών.

### getECIEncoding() {#geteciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού (Extended Channel Interpretation Identifiers). Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### getEncodeMode() {#getencodemode}

Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

### getErrorLevel() {#geterrorlevel}

Αποκτά τον τύπο συμβολής Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, όπου level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, ενώ level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters στο MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Όνομα παραλήπτη barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Άθροισμα ελέγχου (checksum) barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο checksum περιέχει την τιμή του 16-bit (2 byte) CRC checksum χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1.

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417.

### getMacroPdf417FileID() {#getmacropdf417fileid}

Αναγνωριστικό αρχείου (file ID) barcode MacroPdf417 (απαιτούμενο πεδίο). Αναγνωριστικό αρχείου barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append).

### getMacroPdf417FileName() {#getmacropdf417filename}

Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

Αναγνωριστικό τμήματος (segment ID) barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append).

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

Αριθμός τμημάτων barcode MacroPdf417 (προαιρετικό πεδίο). Αριθμός τμημάτων barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### getMacroPdf417Sender() {#getmacropdf417sender}

Όνομα αποστολέα barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### getMacroPdf417Terminator() {#getmacropdf417terminator}

Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει τον Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### getPdf417CompactionMode() {#getpdf417compactionmode}

Τύπος συμβολισμού Pdf417 της λειτουργίας συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση αποτελεί όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### getPdf417EncodeMode() {#getpdf417encodemode}

Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Αποκτά τον τύπο συμβολής Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode, κυμαινόμενο από level0 έως level8, όπου level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, ενώ level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode addressee name.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode checksum.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode's file ID. Χρησιμοποιείται για MacroPdf417.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode file name.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 file size.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode's segment ID, που ξεκινά από 0, έως MacroSegmentsCount - 1.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode segments count.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode sender name.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει τον Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Λαμβάνει macro Pdf417 barcode time stamp.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου).

### getRows() {#getrows}

Αριθμός γραμμών.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### getTruncate() {#gettruncate}

Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο τερματισμού αφαιρούνται σε αυτή τη λειτουργία.

### isCode128Emulation() {#iscode128emulation}

Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση για τις λειτουργίες 908 και 909, καθώς και τις 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτή. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως barcode Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί τις λειτουργίες “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 στο GS1MicroPdf417 και τη σημαία σύνδεσης (918) στα barcode MicroPdf417 και Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη.

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

Λόγος ύψους/πλάτους του μονάδας 2D BarCode.

### setCode128Emulation() {#setcode128emulation}

Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση για τις λειτουργίες 908 και 909, καθώς και τις 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτή. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως barcode Code 128.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

Αριθμός στηλών.

### setECIEncoding() {#seteciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού (Extended Channel Interpretation Identifiers). Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### setEncodeMode() {#setencodemode}

Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

### setErrorLevel(value) {#seterrorlevel}

Ορίζει τον τύπο συμβολισμού Pdf417 του BarCode για το επίπεδο διόρθωσης σφαλμάτων, από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Τύπος συμβολισμού Pdf417 του BarCode για το επίπεδο διόρθωσης σφαλμάτων, από level0 έως level8, level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα. |

### setLinked() {#setlinked}

Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με το σύμβολο GS1MicroPdf417 κωδικοποιεί τις λειτουργίες “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Με τα σύμβολα MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 στο GS1MicroPdf417 και τη σημαία σύνδεσης (918) στα barcode MicroPdf417 και Pdf417.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None. Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters στο MicroPdf417.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

Όνομα παραλήπτη barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### setMacroPdf417Checksum() {#setmacropdf417checksum}

Άθροισμα ελέγχου (checksum) barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο checksum περιέχει την τιμή του 16-bit (2 byte) CRC checksum χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1.

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417.

### setMacroPdf417FileID() {#setmacropdf417fileid}

Αναγνωριστικό αρχείου (file ID) barcode MacroPdf417 (απαιτούμενο πεδίο). Αναγνωριστικό αρχείου barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append).

### setMacroPdf417FileName() {#setmacropdf417filename}

Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### setMacroPdf417FileSize() {#setmacropdf417filesize}

Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

Αναγνωριστικό τμήματος (segment ID) barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append).

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

Αριθμός τμημάτων barcode MacroPdf417 (προαιρετικό πεδίο). Αριθμός τμημάτων barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### setMacroPdf417Sender() {#setmacropdf417sender}

Όνομα αποστολέα barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### setMacroPdf417Terminator() {#setmacropdf417terminator}

Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει τον Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append).

### setPdf417CompactionMode() {#setpdf417compactionmode}

Τύπος συμβολισμού Pdf417 της λειτουργίας συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Η τρέχουσα υλοποίηση αποτελεί όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Ορίζει τον τύπο συμβολισμού Pdf417 του BarCode για το επίπεδο διόρθωσης σφαλμάτων, από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

Ορίζει το όνομα παραλήπτη του macro barcode Pdf417.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

Ορίζει το άθροισμα ελέγχου (checksum) του macro barcode Pdf417.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Το πεδίο checksum περιέχει την τιμή του 16-bit (2 bytes) CRC checksum χρησιμοποιώντας το πολυώνυμο CCITT-16. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

Ορίζει το αναγνωριστικό αρχείου (file ID) του macro barcode Pdf417. Χρησιμοποιείται για MacroPdf417.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

Ορίζει το όνομα αρχείου του macro barcode Pdf417.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

Ορίζει το μέγεθος αρχείου του macro Pdf417.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του αρχικού αρχείου. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

Ορίζει το αναγνωριστικό τμήματος (segment ID) του macro barcode Pdf417, που ξεκινά από 0 έως MacroSegmentsCount - 1.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

Ορίζει τον αριθμό τμημάτων του macro barcode Pdf417.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

Ορίζει το όνομα αποστολέα του macro barcode Pdf417.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει τον Terminator Macro PDF417 (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

Ορίζει τη χρονική σήμανση (time stamp) του macro barcode Pdf417.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

Εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου).

### setReaderInitialization(value) {#setreaderinitialization}

Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την εκκίνηση του αναγνώστη.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή |  |

### setRows() {#setrows}

Αριθμός γραμμών.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Αναγνωρίζει το ID του barcode DotCode σε λειτουργία structured append. Το ID ξεκινά από 1 και πρέπει να είναι μικρότερο ή ίσο με τον αριθμό των barcode. Η προεπιλεγμένη τιμή είναι -1.

### setTruncate() {#settruncate}

Καθορίζει αν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο τερματισμού αφαιρούνται σε αυτή τη λειτουργία.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του Pdf417Parameters.

**Returns:** A string that represents this Pdf417Parameters.

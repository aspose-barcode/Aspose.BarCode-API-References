---
title: "Aspose::BarCode::Generation::Pdf417Parameters κλάση"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::Pdf417Parameters κλάση. Παράμετροι PDF417. Περιλαμβάνει παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία Structured Append (ίδια με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά σε C++."
type: docs
weight: 4000
url: /el/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


Παράμετροι PDF417. Περιλαμβάνει παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία Structured Append (ίδιο με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.

```cpp
class Pdf417Parameters : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [get_Columns](./get_columns/)() const | Αριθμός στηλών. |
| [get_ECIEncoding](./get_eciencoding/)() const | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. |
| [get_EncodeMode](./get_encodemode/)() const | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Λαμβάνει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του [BarCode](../../aspose.barcode/) που κυμαίνεται από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων που οδηγεί σε μεγαλύτερη εικόνα. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης και 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [get_IsLinked](./get_islinked/)() const | Ορίζει συνδεδεμένες λειτουργίες με τα barcodes GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολική GS1MicroPdf417 κωδικοποιεί τις λειτουργίες 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Όνομα παραλήπτη barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Άθροισμα ελέγχου barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | Αναγνωριστικό αρχείου barcode MacroPdf417 (απαιτούμενο πεδίο). Αναγνωριστικό αρχείου barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του πηγαίου αρχείου. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | Αναγνωριστικό τμήματος barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Αριθμός τμημάτων barcode MacroPdf417 (προαιρετικό πεδίο). Αριθμός τμημάτων barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Όνομα αποστολέα barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν θα προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [get_Rows](./get_rows/)() const | Αριθμός γραμμών. |
| [get_Truncate](./get_truncate/)() const | Καθορίζει αν ο τύπος συμβολισμού Pdf417 του [BarCode](../../aspose.barcode/) είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία. |
| [set_AspectRatio](./set_aspectratio/)(float) | Αναλογία ύψους/πλάτους του 2D [BarCode](../../aspose.barcode/) μονάδας. |
| [set_Columns](./set_columns/)(int32_t) | Αριθμός στηλών. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Ορίζει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του [BarCode](../../aspose.barcode/) από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, το level8 σημαίνει την καλύτερη διόρθωση σφαλμάτων που σημαίνει μεγαλύτερη εικόνα. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης και 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [set_IsLinked](./set_islinked/)(bool) | Ορίζει συνδεδεμένες λειτουργίες με τα barcodes GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολική GS1MicroPdf417 κωδικοποιεί τις λειτουργίες 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | Όνομα παραλήπτη barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | Άθροισμα ελέγχου barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 bytes) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Εφαρμόζεται σε πεδία κειμένου Macro PDF417. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | Αναγνωριστικό αρχείου barcode MacroPdf417 (απαιτούμενο πεδίο). Αναγνωριστικό αρχείου barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | Όνομα αρχείου barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε bytes ολόκληρου του πηγαίου αρχείου. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | Αναγνωριστικό τμήματος barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | Αριθμός τμημάτων barcode MacroPdf417 (προαιρετικό πεδίο). Αριθμός τμημάτων barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | Όνομα αποστολέα barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή εάν θα προσθέσει το Macro PDF417 Terminator (codeword 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | Χρονική σήμανση barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [set_Rows](./set_rows/)(int32_t) | Αριθμός γραμμών. |
| [set_Truncate](./set_truncate/)(bool) | Καθορίζει αν ο τύπος συμβολισμού Pdf417 του [BarCode](../../aspose.barcode/) είναι περικομμένος (για μείωση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το [Pdf417Parameters](./). |
## Σχόλια


Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις μη συνδεδεμένες λειτουργίες UCC/EAN-128 στο GS1MicroPdf417.
```cpp
[C#]
//Κωδικοποιεί τη μη συνδεδεμένη λειτουργία 905 του GS1 UCC/EAN-128 με AI 01 (GTIN).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Κωδικοποιεί τις μη συνδεδεμένες λειτουργίες 903, 904 του GS1 UCC/EAN-128 με οποιοδήποτε AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

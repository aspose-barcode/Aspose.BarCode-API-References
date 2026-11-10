---
title: "Κλάση Pdf417Parameters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.Pdf417Parameters κλάση. Παράμετροι PDF417. Περιέχει τις παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία Structured Append, όπως και το MacroPDF417, απαιτεί δύο πεδία Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά."
type: docs
weight: 1570
url: /el/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

Παράμετροι PDF417. Περιλαμβάνει τις παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία Structured Append (ίδιο με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.

```csharp
public class Pdf417Parameters
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Αναλογία Ύψος/Πλάτος του 2D BarCode μονάδας. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Αριθμός στηλών. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού (Extended Channel Interpretation Identifiers). Χρησιμοποιούνται για να ενημερώνουν τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. Προεπιλεγμένη τιμή: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | Ορίζει συνδεδεμένες λειτουργίες με barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολή GS1MicroPdf417 κωδικοποιεί τις λειτουργίες “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με το MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | Άθροισμα ελέγχου (checksum) του barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). Το πεδίο checksum περιέχει την τιμή του 16-bit (2 bytes) CRC checksum χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο). Αναγνωριστικό αρχείου του barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | Όνομα αρχείου του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append) Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε byte ολόκληρου του αρχικού αρχείου. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | Αναγνωριστικό τμήματος του barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος του barcode MicroPDF417 (απαιτούμενο πεδίο για λειτουργία Structured Append). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | Αριθμός τμημάτων του barcode MacroPdf417 (προαιρετικό πεδίο). Αριθμός τμημάτων του barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | Χρονική σήμανση του barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Αριθμός γραμμών. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | Καθορίζει εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένος (για εξοικονόμηση χώρου). Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς γραμμής και το δεξιό μοτίβο τερματισμού αφαιρούνται σε αυτή τη λειτουργία. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του `Pdf417Parameters`. |

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις μη συνδεδεμένες λειτουργίες UCC/EAN-128 στο GS1MicroPdf417.

```csharp
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

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



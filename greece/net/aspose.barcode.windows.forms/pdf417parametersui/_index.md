---
title: "Κλάση Pdf417ParametersUI"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Windows.Forms.Pdf417ParametersUI. Περιτύλιγμα UI για την κλάση Pdf417Parameters."
type: docs
weight: 1860
url: /el/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

Περιτύλιγμα UI για την κλάση [`Pdf417Parameters`](../../aspose.barcode/generation/pdf417parameters/).

```csharp
public class Pdf417ParametersUI
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | Αναλογία Ύψος/Πλάτος του 2D BarCode μονάδας. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Αριθμός στηλών. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού (Extended Channel Interpretation Identifiers). Χρησιμοποιούνται για να ενημερώνουν τον αναγνώστη barcode λεπτομέρειες σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις χαρακτήρων. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | Τύπος συμβολισμού Pdf417 για τη λειτουργία κωδικοποίησης του BarCode. Προεπιλεγμένη τιμή: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμβολισμού Pdf417 για το επίπεδο διόρθωσης σφαλμάτων του BarCode, που κυμαίνεται από level0 έως level8· level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων, level8 σημαίνει τη βέλτιστη διόρθωση σφαλμάτων, η οποία οδηγεί σε μεγαλύτερη εικόνα. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | Ορίζει συνδεδεμένες λειτουργίες με barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολή GS1MicroPdf417 κωδικοποιεί τις λειτουργίες “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την αρχικοποίηση του αναγνώστη. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με το MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | Άθροισμα ελέγχου (checksum) του barcode MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). Το πεδίο checksum περιέχει την τιμή του 16-bit (2 bytes) CRC checksum χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Αναγνωριστικά Επεκταμένης Ερμηνείας Καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Λαμβάνει ή ορίζει το αναγνωριστικό αρχείου (file ID) του macro barcode Pdf417. Χρησιμοποιείται για MacroPdf417. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | Όνομα αρχείου του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append) Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε byte ολόκληρου του αρχικού αρχείου. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Λαμβάνει ή ορίζει το macro Pdf417 barcode's segment ID, το οποίο ξεκινά από 0 έως MacroSegmentsCount - 1. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Λαμβάνει ή ορίζει τον αριθμό τμημάτων του macro Pdf417 barcode. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν πρέπει να προσθέσει το Macro PDF417 Terminator (κωδικός 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | Χρονική σήμανση του barcode MacroPdf417 (προαιρετικό πεδίο). Χρονική σήμανση του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Αριθμός γραμμών. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | Εάν ο τύπος συμβολής Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Επιστρέφει μια αναγνώσιμη από άνθρωπο αλφαριθμητική αναπαράσταση αυτού του [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/). |

### Δείτε επίσης

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)



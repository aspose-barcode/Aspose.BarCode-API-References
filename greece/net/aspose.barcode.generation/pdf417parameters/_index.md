---
title: Pdf417Parameters
second_title: Aspose.BarCode για Αναφορά API .NET
description: PDF417 παράμετροι. Περιέχει παραμέτρους PDF417 MacroPDF417 και MicroPDF417. Το MacroPDF417 απαιτεί δύο πεδία Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία δομημένης προσθήκης ίδια με τη λειτουργία MacroPDF417 απαιτεί δύο πεδία Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.
type: docs
weight: 1130
url: /el/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 παράμετροι. Περιέχει παραμέτρους PDF417, MacroPDF417 και MicroPDF417. Το MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά. Το MicroPDF417 σε λειτουργία δομημένης προσθήκης (ίδια με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.

```csharp
public class Pdf417Parameters
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | Λόγος ύψους/πλάτους μονάδας 2D BarCode. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation/) { get; set; } | Κωδική λέξη συνάρτησης για προσομοίωση Κωδικού 128. Εφαρμόζεται μόνο για MicroPDF417. Αγνοήθηκε για γραμμικούς κώδικες PDF417 και MacroPDF417. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding/) { get; set; } | Λαμβάνει ή ορίζει την κωδικοποίηση του κωδικοποιημένου κειμένου. Προεπιλεγμένη τιμή: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Πλήθος στηλών. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Χρησιμοποιείται για να δώσει οδηγίες στον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο ως προγραμματισμό για την προετοιμασία του αναγνώστη. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode/) { get; set; } | τύπος συμβολολογίας Pdf417 της λειτουργίας συμπίεσης του BarCode. Προεπιλεγμένη τιμή: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding/) { get; set; } | Εκτεταμένα αναγνωριστικά ερμηνείας καναλιού. Χρησιμοποιείται για την ενημέρωση του αναγνώστη γραμμικού κώδικα details σχετικά με τις χρησιμοποιούμενες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται για πεδία κειμένου Macro PDF417. Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο συμβολολογίας Pdf417 του επιπέδου διόρθωσης σφαλμάτων BarCode που κυμαίνεται από το επίπεδο 0 έως το επίπεδο 8, το επίπεδο 0 σημαίνει καμία πληροφορία διόρθωσης σφάλματος, το επίπεδο8 σημαίνει την καλύτερη διόρθωση σφάλματος που σημαίνει μεγαλύτερη εικόνα. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee/) { get; set; } | Όνομα παραλήπτη γραμμικού κώδικα MacroPdf417 (προαιρετικό πεδίο). Όνομα παραλήπτη γραμμικού κώδικα MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum/) { get; set; } | Άθροισμα ελέγχου γραμμικού κώδικα MacroPdf417 (προαιρετικό πεδίο). Άθροισμα ελέγχου γραμμικού κώδικα MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του αθροίσματος ελέγχου CRC 16-bit (2 byte) χρησιμοποιώντας το CCITT-1. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding/) { get; set; } | Εκτεταμένα αναγνωριστικά ερμηνείας καναλιού. Ισχύει για πεδία κειμένου Macro PDF417. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid/) { get; set; } | Αναγνωριστικό αρχείου γραμμικού κώδικα MacroPdf417 (Απαιτούμενο πεδίο). Αναγνωριστικό αρχείου γραμμικού κώδικα MicroPDF417 (Απαιτούμενο πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename/) { get; set; } | Όνομα αρχείου γραμμικού κώδικα MacroPdf417 (προαιρετικό πεδίο). Όνομα αρχείου γραμμικού κώδικα MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize/) { get; set; } | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο). Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε byte ολόκληρου του αρχείου προέλευσης. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid/) { get; set; } | Αναγνωριστικό τμήματος γραμμικού κώδικα MacroPdf417 (Απαιτούμενο πεδίο), το οποίο ξεκινά από 0, έως MacroSegmentsCount - 1. Αναγνωριστικό τμήματος γραμμικού κώδικα MicroPDF417 (Απαιτούμενο πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount/) { get; set; } | Καταμέτρηση τμημάτων γραμμικού κώδικα MacroPdf417 (προαιρετικό πεδίο). Καταμέτρηση τμημάτων γραμμικού κώδικα MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender/) { get; set; } | Όνομα αποστολέα γραμμικού κώδικα MacroPdf417 (προαιρετικό πεδίο). Όνομα αποστολέα γραμμικού κώδικα MicroPDF417 (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417MacroTerminator](../../aspose.barcode.generation/pdf417parameters/pdf417macroterminator/) { get; set; } | Χρησιμοποιείται για να πει στον κωδικοποιητή εάν θα προσθέσει το Macro PDF417 Terminator (κωδική λέξη 922) στο τμήμα. Εφαρμόζεται μόνο για Macro PDF417. |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp/) { get; set; } | Time stamp barcode MacroPdf417 (προαιρετικό πεδίο). MicroPDF417 barcode time stamp (προαιρετικό πεδίο για λειτουργία δομημένης προσθήκης) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate/) { get; set; } | Εάν ο τύπος συμβολολογίας Pdf417 του BarCode είναι περικομμένος (για μείωση χώρου). Γνωστό και ως CompactPDF417. Η ένδειξη της δεξιάς σειράς και το μοτίβο δεξιάς διακοπής καταργούνται σε αυτήν τη λειτουργία. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Αριθμός σειρών. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Επιστρέφει μια αναπαράσταση συμβολοσειράς αναγνώσιμη από τον άνθρωπο`Pdf417Parameters` . |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* συνέλευση [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

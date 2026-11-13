---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

Παράμετροι PDF417. Περιέχει παραμέτρους PDF417, MacroPDF417, MicroPDF417 και GS1MicroPdf417.<br/>MacroPDF417 απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.<br/>MicroPDF417 σε λειτουργία Structured Append (ίδια με τη λειτουργία MacroPDF417) απαιτεί δύο πεδία: Pdf417MacroFileID και Pdf417MacroSegmentID. Όλα τα άλλα πεδία είναι προαιρετικά.

Ο τύπος Pdf417Parameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| encode_mode | Καθορίζει τη λειτουργία κωδικοποίησης Pdf417. <br/>            Προεπιλεγμένη τιμή: Auto. |
| error_level | Αποκτά ή ορίζει τον τύπο συμβολισμού Pdf417 του επιπέδου διόρθωσης σφαλμάτων του BarCode<br/>            κυμαινόμενο από level0 έως level8, το level0 σημαίνει χωρίς πληροφορίες διόρθωσης σφαλμάτων,<br/>            το level8 σημαίνει βέλτιστη διόρθωση σφαλμάτων, η οποία σημαίνει μεγαλύτερη εικόνα. |
| truncate | Καθορίζει εάν ο τύπος συμβολισμού Pdf417 του BarCode είναι περικομμένο (για μείωση χώρου). <br/>            Επίσης γνωστό ως CompactPDF417. Ο δείκτης δεξιάς σειράς και το δεξιό μοτίβο διακοπής αφαιρούνται σε αυτή τη λειτουργία. |
| στήλες | Αριθμός στηλών. |
| γραμμές | Αριθμός γραμμών. |
| aspect_ratio | Αναλογία ύψους/πλάτους του μονάδας 2D BarCode. |
| macro_pdf_417_file_id | Αναγνωριστικό αρχείου του barcode MacroPdf417 (απαιτούμενο πεδίο).<br/>            Αναγνωριστικό αρχείου του barcode MicroPDF417 (απαιτούμενο πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_segment_id | Αναγνωριστικό τμήματος του barcode MacroPdf417 (απαιτούμενο πεδίο), που ξεκινά από 0 έως MacroSegmentsCount - 1.<br/>            Αναγνωριστικό τμήματος του barcode MicroPDF417 (απαιτούμενο πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_segments_count | Αριθμός τμημάτων του barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Αριθμός τμημάτων του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_file_name | Όνομα αρχείου του barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Όνομα αρχείου του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_time_stamp | Χρονική σήμανση του barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Χρονική σήμανση του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_sender | Όνομα αποστολέα του barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Όνομα αποστολέα του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_addressee | Όνομα παραλήπτη του barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Όνομα παραλήπτη του barcode MicroPDF417 (προαιρετικό πεδίο για τη λειτουργία Structured Append). |
| macro_pdf_417_file_size | Μέγεθος αρχείου MacroPdf417 (προαιρετικό πεδίο).<br/>            Μέγεθος αρχείου MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append)<br/>            Το πεδίο μεγέθους αρχείου περιέχει το μέγεθος σε byte ολόκληρου του αρχικού αρχείου. |
| macro_pdf_417_checksum | Άθροισμα ελέγχου barcode MacroPdf417 (προαιρετικό πεδίο).<br/>            Άθροισμα ελέγχου barcode MicroPDF417 (προαιρετικό πεδίο για λειτουργία Structured Append)<br/>            Το πεδίο αθροίσματος ελέγχου περιέχει την τιμή του 16-bit (2 byte) CRC αθροίσματος ελέγχου χρησιμοποιώντας το πολυώνυμο CCITT-16. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Extended Channel Interpretation Identifiers. Χρησιμοποιείται για να ενημερώσει τον αναγνώστη barcode λεπτομέρειες<br/>            σχετικά με τις χρησιμοποιημένες αναφορές για την κωδικοποίηση των δεδομένων στο σύμβολο. Δεν εφαρμόζεται σε πεδία κειμένου Macro PDF417.<br/>            Η τρέχουσα υλοποίηση περιλαμβάνει όλες τις γνωστές κωδικοποιήσεις συνόλων χαρακτήρων. |
| macro_pdf_417eci_encoding | Extended Channel Interpretation Identifiers. Ισχύει για πεδία κειμένου Macro PDF417. |
| macro_pdf_417_terminator | Χρησιμοποιείται για να ενημερώσει τον κωδικοποιητή αν θα προσθέσει τον Τερματικό Macro PDF417 (κωδικός 922) στο τμήμα. <br/>            Εφαρμόζεται μόνο για Macro PDF417. |
| is_reader_initialization | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο<br/>            ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| macro_characters | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για να επιτύχουν πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες.<br/>            Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 του MicroPdf417<br/>            Προεπιλεγμένη τιμή: MacroCharacters.None. |
| is_linked | Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417<br/>            Με τη συμβολή GS1MicroPdf417 κωδικοποιεί τις λειτουργίες 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128<br/>            Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός από ένα EAN.UCC |
| is_code_128_emulation | Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες εξομοίωσης Code 128<br/>            Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση στις λειτουργίες 908 και 909, καθώς μπορεί επίσης να κωδικοποιήσει 910 και 911 που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128 |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


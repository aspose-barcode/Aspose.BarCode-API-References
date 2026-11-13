---
title: "AztecParameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Παράμετροι Aztec.

Ο τύπος AztecParameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| encode_mode | Λαμβάνει ή ορίζει μια λειτουργία κωδικοποίησης Aztec. <br/>            Προεπιλεγμένη τιμή: Auto. |
| eci_encoding | Λαμβάνει ή ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το AztecEncodeMode είναι Auto.<br/>            Προεπιλεγμένη τιμή: ISO-8859-1 |
| structured_append_barcode_id | Αναγνωριστικό Barcode για τη λειτουργία Structured Append του Aztec barcode. Το Barcode ID πρέπει να βρίσκεται στο εύρος από 1 έως τον αριθμό των barcode.<br/>            Προεπιλεγμένη τιμή: 0 |
| structured_append_barcodes_count | Ο αριθμός των barcode για τη λειτουργία Structured Append του κώδικα Aztec. Ο αριθμός των barcode πρέπει να είναι στο εύρος από 1 έως 26.<br/>            Προεπιλεγμένη τιμή: 0 |
| structured_append_file_id | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του κώδικα Aztec (προαιρετικό πεδίο). Το αναγνωριστικό αρχείου δεν πρέπει να περιέχει κενά.<br/>            Προεπιλεγμένη τιμή: κενή συμβολοσειρά |
| error_level | Επίπεδο διόρθωσης σφαλμάτων των τύπων barcode Aztec.<br/>            Η τιμή πρέπει να είναι μεταξύ 5 και 95. |
| symbol_mode | Λαμβάνει ή ορίζει τη λειτουργία Symbol του Aztec.<br/>            Προεπιλεγμένη τιμή: AztecSymbolMode.Auto. |
| layers_count | Λαμβάνει ή ορίζει τον αριθμό των επιπέδων του συμβόλου Aztec. Ο αριθμός των επιπέδων πρέπει να είναι στο εύρος από 1 έως 3 για τη λειτουργία Compact και<br/>            στο εύρος από 1 έως 32 για τη λειτουργία Full Range.<br/>            Προεπιλεγμένη τιμή: 0 (αυτόματο). |
| is_reader_initialization | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο<br/>            ως προγραμματισμό για την εκκίνηση του αναγνώστη. |
| aspect_ratio | Αναλογία ύψους/πλάτους του μονάδας 2D BarCode. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


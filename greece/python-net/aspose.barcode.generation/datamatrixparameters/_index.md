---
title: "DataMatrixParameters"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Παράμετροι DataMatrix.

Ο τύπος DataMatrixParameters εκθέτει τα ακόλουθα μέλη:
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| ecc_type | Λαμβάνει ή ορίζει έναν τύπο ECC του Datamatrix.<br/>            Προεπιλεγμένη τιμή: DataMatrixEccType.Ecc200. |
| version | Λαμβάνει ή ορίζει το μέγεθος συμβόλου Datamatrix.<br/>            Προεπιλεγμένη τιμή: Version.Auto. |
| encode_mode | Λειτουργία κωδικοποίησης του barcode Datamatrix.<br/>            Προεπιλεγμένη τιμή: EncodeMode.Auto. |
| structured_append_barcode_id | Αναγνωριστικό barcode για τη λειτουργία Structured Append του barcode Datamatrix.<br/>            Προεπιλεγμένη τιμή: 0 |
| structured_append_barcodes_count | Αριθμός barcode για τη λειτουργία Structured Append του barcode Datamatrix.<br/>            Προεπιλεγμένη τιμή: 0 |
| structured_append_file_id | Αναγνωριστικό αρχείου για τη λειτουργία Structured Append του barcode Datamatrix.<br/>            Προεπιλεγμένη τιμή: 0 |
| is_reader_programming | Χρησιμοποιείται για να καθοδηγήσει τον αναγνώστη να ερμηνεύσει τα δεδομένα που περιέχονται στο σύμβολο<br/>            ως προγραμματισμό για την αρχικοποίηση του αναγνώστη.<br/>            Προεπιλεγμένη τιμή: false |
| macro_characters | Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες.<br/>            Μπορεί να χρησιμοποιηθεί μόνο με DataMatrixEccType.Ecc200 ή DataMatrixEccType.EccAuto.<br/>            Δεν μπορεί να χρησιμοποιηθεί με EncodeTypes.GS1DataMatrix<br/>            Προεπιλεγμένη τιμή: MacroCharacters.None. |
| aspect_ratio | Αναλογία ύψους/πλάτους του μονάδας 2D BarCode. |
| eci_encoding | Λαμβάνει ή ορίζει την κωδικοποίηση ECI. Χρησιμοποιείται όταν το EncodeMode είναι Auto.<br/>            Προεπιλεγμένη τιμή: ISO-8859-1 |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


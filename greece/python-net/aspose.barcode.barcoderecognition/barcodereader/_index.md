---
title: "BarCodeReader"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

Το BarCodeReader περιλαμβάνει μια εικόνα που μπορεί να περιέχει ένα ή πολλά barcodes, και στη συνέχεια μπορεί να εκτελέσει την ενέργεια ReadBarCodes για την ανίχνευση των barcodes.

Ο τύπος BarCodeReader εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| BarCodeReader() | Αρχικοποιεί μια νέα παρουσία της κλάσης [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) με προεπιλεγμένες τιμές.<br/>            Απαιτεί να οριστεί η εικόνα (SetBitmapImage()) πριν κληθεί η μέθοδος ReadBarCodes(). |
| BarCodeReader(image) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, area, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, area, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(image, areas, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(filename) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(filename, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(filename, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(stream) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(stream, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(stream, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, areas, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, area, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame, decode_types) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
| BarCodeReader(frame) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarCodeReader |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| processor_settings | Λαμβάνει ρυθμίσεις για τη χρήση πυρήνων επεξεργαστή. |
| timeout | Λαμβάνει ή ορίζει το χρονικό όριο της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| found_bar_codes | Λαμβάνει πίνακα των αναγνωρισμένων [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) |
| found_count | Λαμβάνει τον αριθμό των αναγνωρισμένων barcode |
| quality_settings | Το QualitySettings επιτρέπει τη διαμόρφωση της ποιότητας και της ταχύτητας της αναγνώρισης χειροκίνητα.<br/>            Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές.<br/>            Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality. |
| barcode_settings | Οι κύριες παραμέτρους αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα. |
| bar_code_read_type | Λαμβάνει ή ορίζει τον τύπο αποκωδικοποίησης barcode που χρησιμοποιείται για την αναγνώριση.<br/>            Πρέπει να οριστεί πριν από την κλήση του [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| set_bar_code_image(value) | Ορίζει εικόνα bitmap για την αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| set_bar_code_image(value, areas) | Ορίζει εικόνα bitmap και περιοχές για την αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| set_bar_code_image(value, area) | Ορίζει εικόνα bitmap και περιοχές για την αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| set_bar_code_image(filename) | Ορίζει αρχείο εικόνας για την αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| set_bar_code_image(stream) | Ορίζει ροή εικόνας για την αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |
| set_bar_code_image(frame, area) | Ορίζει το πλαίσιο φωτεινότητας και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Ορίζει το πλαίσιο φωτεινότητας και τις περιοχές για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Ορίζει το πλαίσιο φωτεινότητας και την περιοχή για την αναγνώριση. Πρέπει να κληθεί πριν από τη μέθοδο [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο αρχείο xml |
| export_to_xml(xml_stream) | Εξάγει τις ιδιότητες BarCode στη καθορισμένη ροή xml |
| import_from_xml(xml_file) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο αρχείο xml και τις εφαρμόζει στην τρέχουσα παρουσία BarCodeReader. |
| import_from_xml(xml_stream) | Εισάγει τις ιδιότητες BarCode από τη καθορισμένη ροή xml και τις εφαρμόζει στην τρέχουσα παρουσία BarCodeReader. |
| abort() | Η λειτουργία ζητά τη λήξη της τρέχουσας συνεδρίας αναγνώρισης από άλλο νήμα. Η μέθοδος Abort είναι ακατάσβεστη και επιστρέφει τον έλεγχο αμέσως μετά την κλήση. <br/>            Η μέθοδος πρέπει να χρησιμοποιείται όταν η διαδικασία αναγνώρισης διαρκεί πολύ. |
| read_bar_codes() | Διαβάζει [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) από την εικόνα. |
| set_bar_code_read_type(barcode_types) | Ορίζει πίνακα τύπου [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) για αναγνώριση. <br/>            Πρέπει να κληθεί πριν από τη μέθοδο ReadBarCodes(). |

### Δείτε επίσης

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)


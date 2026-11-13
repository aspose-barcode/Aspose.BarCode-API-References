---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator για δημιουργία εικόνων barcode στο backend.

Ο τύπος BarcodeGenerator εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| BarcodeGenerator(type) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Αρχικοποιεί μια νέα παρουσία της κλάσης BarcodeGenerator |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| parameters | Παράμετροι δημιουργίας. |
| barcode_type | Τύπος συμβολισμού Barcode. |
| code_text | Κείμενο προς κωδικοποίηση. |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| set_code_text(code_bytes) | Ορίζει το κείμενο κώδικα ως ακολουθία byte. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Αποθηκεύει την εικόνα barcode σε ροή σε συγκεκριμένη μορφή. |
| save(filename, format) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| save(filename) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| export_to_xml(xml_file) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο αρχείο xml |
| export_to_xml(xml) | Εξάγει τις ιδιότητες BarCode στη καθορισμένη ροή xml |
| import_from_xml(xml_file) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο αρχείο xml και δημιουργεί μια παρουσία BarcodeGenerator. |
| import_from_xml(xml) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο ροή xml και δημιουργεί μια παρουσία BarcodeGenerator. |
| generate_bar_code_image() | Δημιουργεί την εικόνα barcode με τις τρέχουσες ρυθμίσεις. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


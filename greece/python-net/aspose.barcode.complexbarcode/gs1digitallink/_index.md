---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Αντιπροσωπεύει το κείμενο κώδικα GS1 Digital Link για κωδικοποίηση και αποκωδικοποίηση ως μια διατεταγμένη ακολουθία των<br/>            στοιχείων Αναγνωριστικού Εφαρμογής. Η σειρά προέλευσης και τα επαναλαμβανόμενα Αναγνωριστικά Εφαρμογής διατηρούνται.<br/>            Το κατασκευασμένο κείμενο κώδικα είναι ένα μη συμπιεσμένο URI GS1 Digital Link.<br/>            Οι μη‑GS1 παράμετροι ερωτήματος και τα τμήματα URI αγνοούνται κατά την ανάλυση.

Ο τύπος GS1DigitalLink εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| GS1DigitalLink(uri_stem) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GS1DigitalLink |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| uri_stem | Λαμβάνει το απόλυτο πρόθεμα URI πριν από το τμήμα διαδρομής του πρωτεύοντος κλειδιού GS1.<br/>            Το πρόθεμα δεν περιέχει συμβολοσειρά ερωτήματος ή απόσπασμα. |
| primary_application_identifier | Λαμβάνει το Αναγνωριστικό Εφαρμογής που χρησιμοποιείται ως πρωτεύον κλειδί του Digital Link.<br/>            Null σημαίνει ότι το πρωτεύον κλειδί επιλέγεται αυτόματα όταν κατασκευάζεται το URI. |
| barcode_type | Λαμβάνει ή ορίζει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link.<br/>            Οι υποστηριζόμενοι τύποι είναι QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF και Code128.<br/>            Η προεπιλεγμένη τιμή είναι QR. |
| count | Λαμβάνει τον αριθμό των στοιχείων Αναγνωριστικού Εφαρμογής. |
| στοιχεία | Λαμβάνει ένα αντίγραφο όλων των στοιχείων με τη σειρά προέλευσης. |
## Indexer
| Όνομα | Περιγραφή |
| :- | :- |
| [index] | Λαμβάνει ένα στοιχείο με βάση τη θέση του στην ταξινομημένη ακολουθία. |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| create(uri_stem, codetext) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το GS1 codetext και επιλέγοντας<br/>            το μοναδικό διαθέσιμο πρωτεύον κλειδί. |
| create(uri_stem, codetext, primary_application_identifier) | Δημιουργεί ένα GS1 Digital Link αντιγράφοντας όλα τα στοιχεία από το GS1 codetext και επιλέγοντας<br/>            το μοναδικό διαθέσιμο πρωτεύον κλειδί. |
| get_first(application_identifier) | Λαμβάνει την πρώτη τιμή για ένα Application Identifier. |
| get_all(application_identifier) | Λαμβάνει όλες τις τιμές για ένα Application Identifier με τη σειρά προέλευσης. |
| add(application_identifier, value) | Προσθέτει ένα επικυρωμένο στοιχείο Application Identifier. |
| validate(value) | Επικυρώνει ένα μη συμπιεσμένο GS1 Digital Link URI χωρίς τη δημιουργία αντικειμένου. |
| parse(value) | Αναλύει ένα μη συμπιεσμένο GS1 Digital Link URI. |
| try_parse(value, result, validation_result) | Προσπαθεί να αναλύσει ένα μη συμπιεσμένο GS1 Digital Link URI και επιστρέφει δομημένα σφάλματα επικύρωσης. |
| to_gs1_codetext() | Δημιουργεί ένα ανεξάρτητο GS1 codetext που περιέχει τα τρέχοντα στοιχεία GS1.<br/>            Δεν περιλαμβάνονται πληροφορίες μόνο για URI. |
| to_uri_string() | Διαμορφώνει την τρέχουσα κατάσταση του αντικειμένου ως μη συμπιεσμένο GS1 Digital Link URI. |
| get_constructed_codetext() | Κατασκευάζει το μη συμπιεσμένο GS1 Digital Link URI. |
| init_from_string(constructed_codetext) | Αρχικοποιεί αυτήν την παρουσία από ένα μη συμπιεσμένο GS1 Digital Link URI.<br/>            Η υπάρχουσα κατάσταση αντικαθίσταται μόνο μετά την επιτυχή ανάλυση του παρεχόμενου URI.<br/>            Ο επιλεγμένος τύπος barcode διατηρείται. |
| get_barcode_type() | Λαμβάνει τον τύπο barcode που χρησιμοποιείται για την κωδικοποίηση αυτού του GS1 Digital Link. |

### Δείτε επίσης

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


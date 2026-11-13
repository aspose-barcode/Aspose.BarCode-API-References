---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Κλάση για αποθήκευση των δευτερευόντων και πρόσθετων δεδομένων HIBC LIC.

Ο τύπος SecondaryAndAdditionalData εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| SecondaryAndAdditionalData() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης SecondaryAndAdditionalData |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| expiry_date_format | Αναγνωρίζει τη μορφή ημερομηνίας λήξης. |
| expiry_date | Αναγνωρίζει την ημερομηνία λήξης. Θα χρησιμοποιηθεί εάν το ExpiryDateFormat δεν έχει οριστεί σε None. |
| lot_number | Αναγνωρίζει αριθμό παρτίδας ή δέσμης. Ο αριθμός παρτίδας/δέσμης πρέπει να είναι αλφαριθμητικό με μήκος έως 18 σύμβολα. . |
| serial_number | Αναγνωρίζει σειριακό αριθμό. Ο σειριακός αριθμός πρέπει να είναι αλφαριθμητικό με μήκος έως 18 σύμβολα. |
| date_of_manufacture | Αναγνωρίζει ημερομηνία κατασκευής.<br/>            Η ημερομηνία κατασκευής μπορεί να οριστεί σε DateTime.MinValue ώστε να μην χρησιμοποιηθεί αυτό το πεδίο.<br/>            Προεπιλεγμένη τιμή: DateTime.MinValue |
| quantity | Αναγνωρίζει ποσότητα, πρέπει να είναι ακέραια τιμή από 0 έως 500. <br/>            Η ποσότητα μπορεί να οριστεί σε -1 ώστε να μην χρησιμοποιηθεί αυτό το πεδίο.<br/>            Προεπιλεγμένη τιμή: -1 |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Δημιουργεί δευτερεύοντα και πρόσθετα συμπληρωματικά δεδομένα από μορφή συμβολοσειράς σύμφωνα με την προδιαγραφή HIBC LIC. |

### Δείτε επίσης

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


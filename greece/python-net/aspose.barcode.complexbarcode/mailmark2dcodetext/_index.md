---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα Royal Mail 2D Mailmark.

Η Mailmark2DCodetext τύπος εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| Mailmark2DCodetext() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Mailmark2DCodetext |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| upu_country_id | Αναγνωρίζει το UPU Country ID. Μέγιστο μήκος: 4 χαρακτήρες. |
| information_type_id | Αναγνωρίζει το φορτίο του barcode Mailmark της Royal Mail για κάθε τύπο προϊόντος. |
| version_id | Αναγνωρίζει την έκδοση του barcode όπως σχετίζεται με κάθε Information Type ID. |
| klass | Αναγνωρίζει την κλάση του αντικειμένου. |
| supply_chain_id | Αναγνωρίζει τη μοναδική ομάδα πελατών που συμμετέχουν στην αποστολή.<br/>            Μέγιστη τιμή: 9999999. |
| item_id | Αναγνωρίζει το μοναδικό στοιχείο εντός του Supply Chain ID.<br/>            Κάθε barcode Mailmark πρέπει να περιέχει ένα ID<br/>            ώστε να μπορεί να αναγνωρίζεται μοναδικά για τουλάχιστον 90 ημέρες.<br/>            Μέγιστη τιμή: 99999999. |
| destination_post_code_and_dps | Περιέχει τον Ταχυδρομικό Κώδικα της Διεύθυνσης Παράδοσης με DPS<br/>            Εάν είναι ενδοχώρα, ο Ταχυδρομικός Κώδικας/DP περιέχει τον ακόλουθο αριθμό χαρακτήρων.<br/>            Περιοχή (1 ή 2 χαρακτήρες) Περιφέρεια (1 ή 2 χαρακτήρες)<br/>            Τομέας (1 χαρακτήρας) Μονάδα (2 χαρακτήρες) DPS (2 χαρακτήρες).<br/>            Ο Ταχυδρομικός Κώδικας και το DPS πρέπει να συμμορφώνονται με έγκυρη μορφή PAF®. |
| rts_flag | Σημαία που υποδεικνύει ποιο επίπεδο υπηρεσίας Return to Sender ζητείται. |
| return_to_sender_post_code | Περιέχει τον Ταχυδρομικό Κώδικα Return to Sender αλλά χωρίς DPS.<br/>            Ο κώδικας (χωρίς DPS) πρέπει να συμμορφώνεται με μορφή PAF®. |
| customer_content | Προαιρετικός χώρος για χρήση από τον πελάτη. |
| customer_content_encode_mode | Λειτουργία κωδικοποίησης του barcode Datamatrix.<br/>            Προεπιλεγμένη τιμή: EncodeMode.C40. |
| data_matrix_type | Ο τύπος 2D Mailmark ορίζει το μέγεθος του barcode Data Matrix. |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| get_constructed_codetext() | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| init_from_string(constructed_codetext) | Αρχικοποιεί τα δεδομένα Mailmark από το δημιουργημένο κείμενο κώδικα. |
| get_barcode_type() | Λαμβάνει τον τύπο barcode. |

### Δείτε επίσης

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


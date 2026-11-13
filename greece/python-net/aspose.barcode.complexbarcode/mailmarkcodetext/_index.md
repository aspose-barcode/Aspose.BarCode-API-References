---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode για Python μέσω .NET API Reference"
description: 
type: docs
url: /el/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Κλάση για κωδικοποίηση και αποκωδικοποίηση του κειμένου που ενσωματώνεται στον κώδικα 4‑κατάστασης Royal Mailmark.

Ο τύπος MailmarkCodetext εκθέτει τα ακόλουθα μέλη:
## Κατασκευαστές
| Όνομα | Περιγραφή |
| :- | :- |
| MailmarkCodetext() | Αρχικοποιεί μια νέα παρουσία της κλάσης MailmarkCodetext |
## Ιδιότητες
| Όνομα | Περιγραφή |
| :- | :- |
| format | "0" – Κενό ή Δοκιμή<br/>            "1" – Γράμμα<br/>            "2" – Μεγάλο Γράμμα |
| version_id | Προς το παρόν "1" – Για γραμμωτό κώδικα Mailmark (0 και 2 έως 9 και A έως Z διατηρούνται για μελλοντική χρήση) |
| klass | "0" - Κενό ή Δοκιμή<br/>            "1" - 1C (Λιανική)<br/>            "2" - 2C (Λιανική)<br/>            "3" - 3C (Λιανική)<br/>            "4" - Premium (Λιανική Δημοσίευση Mail) (για πιθανή μελλοντική χρήση)<br/>            "5" - Αναβαλλόμενο (Λιανική)<br/>            "6" - Αεροπορική (Λιανική) (για πιθανή μελλοντική χρήση)<br/>            "7" - Επιφάνεια (Λιανική) (για πιθανή μελλοντική χρήση)<br/>            "8" - Premium (Πρόσβαση Δικτύου)<br/>            "9" - Standard (Πρόσβαση Δικτύου) |
| supply_chain_id | Οι μέγιστες τιμές είναι 99 για τον Barcode C και 999999 για τον Barcode L. |
| item_id | Η μέγιστη τιμή είναι 99999999. |
| destination_post_code_and_dps | Το PC και το DP πρέπει να συμμορφώνονται με μορφή PAF.<br/>            Συμβολοσειρά εννέα χαρακτήρων που δηλώνει διεθνές "XY11     " (σημειώστε τα 5 τελικά κενά) ή ένα μοτίβο<br/>            χαρακτήρων που δηλώνει εσωτερικό κωδικό ταξινόμησης.<br/>            Ένας εσωτερικός κωδικός ταξινόμησης αποτελείται από εξωτερικό ταχυδρομικό κώδικα, εσωτερικό ταχυδρομικό κώδικα και κατάληξη σημείου παράδοσης. |
## Μέθοδοι
| Όνομα | Περιγραφή |
| :- | :- |
| get_constructed_codetext() | Δημιουργήστε κείμενο κώδικα από τα δεδομένα Mailmark. |
| init_from_string(constructed_codetext) | Αρχικοποιεί τα δεδομένα Mailmark από το δημιουργημένο κείμενο κώδικα. |
| get_barcode_type() | Λαμβάνει τον τύπο barcode. |

### Δείτε επίσης

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)


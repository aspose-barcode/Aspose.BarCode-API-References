---
title: "QREncodeMode"
second_title: "Aspose.Sildes για Python μέσω .NET API Αναφορά"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Λειτουργία κωδικοποίησης για γραμμωτού κώδικα QR.

## Members
| Όνομα μέλους | Περιγραφή |
| :- | :- |
| AUTO | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. <br/>            Οι χαρακτήρες Unicode κωδικοποιούνται σε λειτουργία kanji εάν είναι δυνατόν, ή κωδικοποιούνται ξανά με την κωδικοποίηση ECIEncoding που έχει οριστεί, με την εισαγωγή ενός αναγνωριστικού ECI.<br/>            Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. |
| EXTENDED |  |
| BINARY | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. <br/>            Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά με την κωδικοποίηση ECIEncoding που έχει οριστεί, με την εισαγωγή ενός αναγνωριστικού ECI.<br/>            Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση.<br/>            Παρακαλούμε σημειώστε ότι ορισμένα παλιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία.<br/>            Αυτή η λειτουργία δεν υποστηρίζεται από τα barcode MicroQR. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


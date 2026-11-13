---
title: "HanXinEncodeMode"
second_title: "Aspose.Sildes για Python μέσω .NET API Αναφορά"
description: 
type: docs
url: /el/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Λειτουργία κωδικοποίησης Han Xin Code. Συνιστάται η χρήση της αυτόματης λειτουργίας με χαρακτήρες ASCII / Κινέζικους ή Unicode για χαρακτήρες Unicode.

## Members
| Όνομα μέλους | Περιγραφή |
| :- | :- |
| AUTO | Στη λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. <br/>            Οι χαρακτήρες Unicode κωδικοποιούνται χρησιμοποιώντας κωδικοποίηση GB18030 σύμφωνα με την προδιαγραφή του κώδικα HanXin. |
| BINARY | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. <br/>            Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI.<br/>            Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση.<br/>            Παρακαλούμε σημειώστε ότι ορισμένοι παλιοί (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |
| UNICODE | Η λειτουργία Unicode σχεδιάζει έναν τρόπο να αντιπροσωπεύει οποιαδήποτε κειμενικά δεδομένα με αναφορά στην κωδικοποίηση/σύνολο χαρακτήρων UTF8 στον κώδικα Han Xin. |
| URI | Η λειτουργία URI υποδεικνύει ότι τα δεδομένα που αντιπροσωπεύονται στον κώδικα Han Xin είναι Uniform Resource Identifier (URI)<br/>            αναφορά στο RFC 3986. |
| EXTENDED | Η λειτουργία Extended επιτρέπει συνδυασμούς εσωτερικών λειτουργιών: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Το Codetext μπορεί να δημιουργηθεί χειροκίνητα με προθέματα και διπλές ανάστροφες καθέτους, π.χ.: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" ή χρησιμοποιώντας το HanXinExtCodetextBuilder.<br/>            Εάν το codetext περιέχει ένα τμήμα ECI, τότε μόνο οι ακόλουθες λειτουργίες μπορούν να βρίσκονται σε αυτό το codetext μετά το τμήμα ECI:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Δείτε επίσης

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


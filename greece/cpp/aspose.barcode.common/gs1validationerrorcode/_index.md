---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Αναγνωρίζει σφάλμα επικύρωσης συμβολοσειράς στοιχείου GS1, Digital Link URI ή τιμής σε C++."
type: docs
weight: 600
url: /el/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Αναγνωρίζει μια συμβολοσειρά στοιχείου GS1, URI Digital Link ή σφάλμα επικύρωσης τιμής.

```cpp
enum class GS1ValidationErrorCode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| EmptyElementString | 0 | Η παρεχόμενη συμβολοσειρά στοιχείου GS1 είναι κενή. |
| MissingOpeningParenthesis | 1 | Λείπει μια αριστερή παρένθεση που θα έπρεπε να ξεκινά ένα Αναγνωριστικό Εφαρμογής. |
| MissingClosingParenthesis | 2 | Ένα Αναγνωριστικό Εφαρμογής δεν έχει δεξιά παρένθεση. |
| InvalidApplicationIdentifier | 3 | Ένα Αναγνωριστικό Εφαρμογής δεν περιέχει δύο έως τέσσερα ψηφία ASCII. |
| UnknownApplicationIdentifier | 4 | Το παρεχόμενο Αναγνωριστικό Εφαρμογής δεν ορίζεται από το υποστηριζόμενο Λεξικό Συντακτικού GS1. |
| MissingValue | 5 | Ένα Αναγνωριστικό Εφαρμογής υπάρχει χωρίς τιμή. |
| InvalidEscapeSequence | 6 | Μια τιμή περιέχει μια μη υποστηριζόμενη ακολουθία διαφυγής. Υποστηρίζεται μόνο (. |
| ValueTooShort | 7 | Μια τιμή είναι πιο σύντομη από το ελάχιστο μήκος που ορίζεται για το Αναγνωριστικό Εφαρμογής της. |
| ValueTooLong | 8 | Μια τιμή είναι μεγαλύτερη από το μέγιστο μήκος που ορίζεται για το Αναγνωριστικό Εφαρμογής της. |
| InvalidCharacter | 9 | Μια τιμή περιέχει έναν χαρακτήρα εκτός του επιτρεπτού συνόλου χαρακτήρων για το στοιχείο της. |
| InvalidChecksum | 10 | Ένας αριθμητικός ή αλφαβητικός έλεγχος αθροίσματος είναι άκυρος. |
| InvalidDate | 11 | Ένα στοιχείο ημερομηνίας δεν αποτελεί έγκυρη ημερομηνία σύμφωνα με τους κανόνες που ορίζονται για το Αναγνωριστικό Εφαρμογής. |
| InvalidTime | 12 | Ένα στοιχείο ώρας βρίσκεται εκτός του επιτρεπτού εύρους του ή έχει άκυρη δομή. |
| InvalidCodeListValue | 13 | Μια τιμή στοιχείου δεν υπάρχει στη επιτρεπόμενη κλειστή λίστα κωδίκων. |
| InvalidComponentLength | 14 | Ένα στοιχείο δεν ικανοποιεί τη δομή μήκους που του είναι ειδική. |
| TruncatedComponent | 15 | Ένα στοιχείο σταθερού μήκους λήγει πριν εμφανιστούν όλοι οι απαιτούμενοι χαρακτήρες. |
| UnexpectedData | 16 | Τα δεδομένα παραμένουν μετά την κατανάλωση όλων των στοιχείων που ορίζονται για το Αναγνωριστικό Εφαρμογής. |
| InvalidValue | 17 | Ένα στοιχείο παραβιάζει έναν κανόνα περιεχομένου που δεν έχει πιο συγκεκριμένο κωδικό σφάλματος επικύρωσης. |
| GcpPrefixTooShort | 18 | Ένα στοιχείο είναι πολύ μικρό για να περιέχει το ελάχιστο τετραψήφιο δομικό πρόθεμα εταιρείας GS1. |
| InvalidGcpPrefix | 19 | Το δομικό πρόθεμα εταιρείας GS1 περιέχει έναν χαρακτήρα που δεν είναι ψηφίο ASCII. |
| InvalidDigitalLinkUri | 20 | Η παρεχόμενη τιμή δεν είναι ένα σωστά διαμορφωμένο απόλυτο URI GS1 Digital Link. |
| UnsupportedDigitalLinkScheme | 21 | Ένα URI GS1 Digital Link χρησιμοποιεί ένα σχήμα διαφορετικό από HTTP ή HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | Η διαδρομή ενός URI GS1 Digital Link δεν περιέχει ένα υποστηριζόμενο πρωτεύον κλειδί. |
| InvalidDigitalLinkPath | 23 | Η διαδρομή ενός URI GS1 Digital Link δεν αποτελείται από έγκυρα ζεύγη AI και τιμής. |
| InvalidDigitalLinkQualifier | 24 | Ένας Αναγνωριστής Εφαρμογής διαδρομής δεν είναι επιτρεπτός προσδιοριστής σε αυτή τη θέση. |
| InvalidDigitalLinkQueryParameter | 25 | Μία GS1 Digital Link query parameter είναι κατεστραμμένη. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Ένα Application Identifier δεν επιτρέπεται ως χαρακτηριστικό δεδομένων GS1 Digital Link. |
| InvalidPercentEncoding | 27 | Ένα GS1 Digital Link URI component περιέχει κατεστραμμένη κωδικοποίηση ποσοστών. |
| MultipleDigitalLinkPrimaryKeys | 28 | Περισσότερα από ένα στοιχείο θα μπορούσε να επιλεγεί ως πρωτεύον κλειδί του GS1 Digital Link. |
| UnsupportedElementCombination | 29 | Ο συνδυασμός των παρεχόμενων στοιχείων GS1 δεν υποστηρίζεται από την επιλεγμένη συμβολική γραφή ή λειτουργία κωδικοποίησης. |

## Δείτε επίσης

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes για Python μέσω .NET API Αναφορά"
description: 
type: docs
url: /el/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Αναγνωρίζει ένα σφάλμα επικύρωσης συμβολοσειράς στοιχείου GS1, Digital Link URI ή τιμής.

## Members
| Όνομα μέλους | Περιγραφή |
| :- | :- |
| EMPTY_ELEMENT_STRING | Η παρεχόμενη συμβολοσειρά στοιχείου GS1 είναι κενή. |
| MISSING_OPENING_PARENTHESIS | Λείπει μια αριστερή παρένθεση που θα έπρεπε να αρχίζει ένα Application Identifier. |
| MISSING_CLOSING_PARENTHESIS | Ένα Application Identifier δεν έχει δεξιά παρένθεση. |
| INVALID_APPLICATION_IDENTIFIER | Ένα Application Identifier δεν περιέχει δύο έως τέσσερα ψηφία ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | Το παρεχόμενο Application Identifier δεν ορίζεται από το υποστηριζόμενο Λεξικό Σύνταξης GS1. |
| MISSING_VALUE | Ένα Application Identifier υπάρχει χωρίς τιμή. |
| INVALID_ESCAPE_SEQUENCE | Μια τιμή περιέχει μια μη υποστηριζόμενη ακολουθία διαφυγής. Μόνο \( υποστηρίζεται. |
| VALUE_TOO_SHORT | Μια τιμή είναι πιο σύντομη από το ελάχιστο μήκος που ορίζεται για το Application Identifier της. |
| VALUE_TOO_LONG | Μια τιμή είναι πιο μακριά από το μέγιστο μήκος που ορίζεται για το Application Identifier της. |
| INVALID_CHARACTER | Μια τιμή περιέχει έναν χαρακτήρα εκτός του συνόλου χαρακτήρων που επιτρέπεται για το στοιχείο της. |
| INVALID_CHECKSUM | Μια αριθμητική ή αλφαβητική άθροιση ελέγχου είναι άκυρη. |
| INVALID_DATE | Ένα στοιχείο ημερομηνίας δεν είναι μια έγκυρη ημερομηνία σύμφωνα με τους κανόνες που ορίζονται για το Application Identifier της. |
| INVALID_TIME | Ένα στοιχείο χρόνου βρίσκεται εκτός του επιτρεπτού εύρους του ή έχει μη έγκυρη δομή. |
| INVALID_CODE_LIST_VALUE | Μια τιμή στοιχείου δεν υπάρχει στην επιτρεπόμενη κλειστή λίστα κωδικών της. |
| INVALID_COMPONENT_LENGTH | Ένα στοιχείο δεν ικανοποιεί τη δομή μήκους που είναι ειδική για το στοιχείο. |
| TRUNCATED_COMPONENT | Ένα στοιχείο σταθερού μήκους λήγει πριν εμφανιστούν όλοι οι απαιτούμενοι χαρακτήρες. |
| UNEXPECTED_DATA | Τα δεδομένα παραμένουν μετά την κατανάλωση όλων των στοιχείων που ορίζονται για το Αναγνωριστικό Εφαρμογής. |
| INVALID_VALUE | Ένα στοιχείο παραβιάζει έναν κανόνα περιεχομένου που δεν έχει πιο συγκεκριμένο κωδικό σφάλματος επικύρωσης. |
| GCP_PREFIX_TOO_SHORT | Ένα στοιχείο είναι πολύ σύντομο για να περιέχει το ελάχιστο τετραψήφιο δομικό πρόθεμα εταιρείας GS1. |
| INVALID_GCP_PREFIX | Το δομικό πρόθεμα εταιρείας GS1 περιέχει χαρακτήρα που δεν είναι ψηφίο ASCII. |
| INVALID_DIGITAL_LINK_URI | Η παρεχόμενη τιμή δεν είναι ένα σωστά διαμορφωμένο απόλυτο URI ψηφιακού συνδέσμου GS1. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Ένα URI ψηφιακού συνδέσμου GS1 χρησιμοποιεί σχήμα διαφορετικό από HTTP ή HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Η διαδρομή ενός URI ψηφιακού συνδέσμου GS1 δεν περιέχει ένα υποστηριζόμενο πρωτεύον κλειδί. |
| INVALID_DIGITAL_LINK_PATH | Η διαδρομή ενός URI ψηφιακού συνδέσμου GS1 δεν αποτελείται από έγκυρα ζεύγη AI και τιμής. |
| INVALID_DIGITAL_LINK_QUALIFIER | Ένα Αναγνωριστικό Εφαρμογής διαδρομής δεν είναι επιτρεπόμενος προσδιοριστής σε αυτή τη θέση. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Μια παράμετρος ερωτήματος GS1 Digital Link είναι εσφαλμένη. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Ένα Αναγνωριστικό Εφαρμογής δεν επιτρέπεται ως χαρακτηριστικό δεδομένων GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Ένα στοιχείο URI του GS1 Digital Link περιέχει εσφαλμένη κωδικοποίηση ποσοστών. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Περισσότερα από ένα στοιχεία μπορούν να επιλεγούν ως το κύριο κλειδί του GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | Ο παρεχόμενος συνδυασμός στοιχείων GS1 δεν υποστηρίζεται από την επιλεγμένη συμβολική ή λειτουργία κωδικοποίησης. |

### Δείτε επίσης

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)


---
title: "Απαρίθμηση GS1ValidationErrorCode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Αναγνωρίζει μια συμβολοσειρά στοιχείου GS1 Digital Link URI ή σφάλμα επικύρωσης τιμής"
type: docs
weight: 430
url: /el/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Αναγνωρίζει μια συμβολοσειρά στοιχείου GS1, URI Digital Link ή σφάλμα επικύρωσης τιμής.

```csharp
public enum GS1ValidationErrorCode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| EmptyElementString | `0` | Η παρεχόμενη συμβολοσειρά στοιχείου GS1 είναι κενή. |
| MissingOpeningParenthesis | `1` | Λείπει μια ανοιχτή παρένθεση που θα έπρεπε να αρχίζει έναν Αναγνωριστικό Εφαρμογής. |
| MissingClosingParenthesis | `2` | Ένας Αναγνωριστικός Εφαρμογής δεν έχει κλειστή παρένθεση. |
| InvalidApplicationIdentifier | `3` | Ένας Αναγνωριστικός Εφαρμογής δεν περιέχει δύο έως τέσσερα ψηφία ASCII. |
| UnknownApplicationIdentifier | `4` | Ο παρεχόμενος Αναγνωριστικός Εφαρμογής δεν ορίζεται από το υποστηριζόμενο Λεξικό Συντακτικού GS1. |
| MissingValue | `5` | Ένας Αναγνωριστικός Εφαρμογής υπάρχει χωρίς τιμή. |
| InvalidEscapeSequence | `6` | Μια τιμή περιέχει μια μη υποστηριζόμενη ακολουθία διαφυγής. Μόνο \\( υποστηρίζεται. |
| ValueTooShort | `7` | Μια τιμή είναι μικρότερη από το ελάχιστο μήκος που ορίζεται για τον Αναγνωριστικό Εφαρμογής της. |
| ValueTooLong | `8` | Μια τιμή είναι μεγαλύτερη από το μέγιστο μήκος που ορίζεται για τον Αναγνωριστικό Εφαρμογής της. |
| InvalidCharacter | `9` | Μια τιμή περιέχει χαρακτήρα εκτός του συνόλου χαρακτήρων που επιτρέπεται για το στοιχείο της. |
| InvalidChecksum | `10` | Ένας αριθμητικός ή αλφαβητικός έλεγχος αθροίσματος είναι άκυρος. |
| InvalidDate | `11` | Ένα στοιχείο ημερομηνίας δεν είναι μια έγκυρη ημερομηνία σύμφωνα με τους κανόνες που ορίζονται για τον Αναγνωριστικό Εφαρμογής του. |
| InvalidTime | `12` | Ένα στοιχείο ώρας είναι εκτός του επιτρεπτού εύρους του ή έχει μη έγκυρη δομή. |
| InvalidCodeListValue | `13` | Μια τιμή στοιχείου δεν υπάρχει στη επιτρεπόμενη κλειστή λίστα κωδικών. |
| InvalidComponentLength | `14` | Ένα στοιχείο δεν ικανοποιεί τη δομή μήκους που είναι ειδική για αυτό. |
| TruncatedComponent | `15` | Ένα στοιχείο σταθερού μήκους λήγει πριν εμφανιστούν όλοι οι απαιτούμενοι χαρακτήρες. |
| UnexpectedData | `16` | Παραμένουν δεδομένα μετά την κατανάλωση όλων των στοιχείων που ορίζονται για τον Αναγνωριστικό Εφαρμογής. |
| InvalidValue | `17` | Ένα στοιχείο παραβιάζει έναν κανόνα περιεχομένου που δεν έχει πιο συγκεκριμένο κωδικό σφάλματος επικύρωσης. |
| GcpPrefixTooShort | `18` | Ένα στοιχείο είναι πολύ μικρό για να περιέχει το ελάχιστο τετραψήφιο δομικό πρόθεμα εταιρείας GS1. |
| InvalidGcpPrefix | `19` | Η δομική GS1 Company Prefix περιέχει έναν χαρακτήρα διαφορετικό από ένα ψηφίο ASCII. |
| InvalidDigitalLinkUri | `20` | Η παρεχόμενη τιμή δεν είναι ένα σωστά διαμορφωμένο απόλυτο GS1 Digital Link URI. |
| UnsupportedDigitalLinkScheme | `21` | Ένα GS1 Digital Link URI χρησιμοποιεί ένα σχήμα διαφορετικό από HTTP ή HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | Η διαδρομή ενός GS1 Digital Link URI δεν περιέχει ένα υποστηριζόμενο πρωτεύον κλειδί. |
| InvalidDigitalLinkPath | `23` | Η διαδρομή ενός GS1 Digital Link URI δεν αποτελείται από έγκυρα ζεύγη AI και τιμής. |
| InvalidDigitalLinkQualifier | `24` | Ένα Application Identifier διαδρομής δεν είναι επιτρεπτός προσδιοριστής σε αυτή τη θέση. |
| InvalidDigitalLinkQueryParameter | `25` | Μια παράμετρος ερωτήματος GS1 Digital Link είναι κακοδιαμορφωμένη. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Ένα Application Identifier δεν επιτρέπεται ως χαρακτηριστικό δεδομένων GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Ένα στοιχείο GS1 Digital Link URI περιέχει κακοδιαμορφωμένη κωδικοποίηση ποσοστών. |
| MultipleDigitalLinkPrimaryKeys | `28` | Περισσότερο από ένα στοιχείο θα μπορούσε να επιλεγεί ως το πρωτεύον κλειδί GS1 Digital Link. |
| UnsupportedElementCombination | `29` | Ο συνδυασμός των παρεχόμενων στοιχείων GS1 δεν υποστηρίζεται από την επιλεγμένη συμβολική ή λειτουργία κωδικοποίησης. |

### Δείτε επίσης

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



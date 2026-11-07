---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Λειτουργία κωδικοποίησης του κωδικοποιητή DataMatrix, προεπιλογή Auto σε C++."
type: docs
weight: 6300
url: /el/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Λειτουργία κωδικοποίησης του κωδικοποιητή DataMatrix, προεπιλογή Auto

```cpp
enum class DataMatrixEncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Αυτόματο | 0 | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. |
| ASCII | 1 | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte |
| C40 | 8 | Χρησιμοποιεί κωδικοποίηση C40. Κωδικοποιεί αλφαριθμητικούς κεφαλαίους, πεζούς και ειδικούς χαρακτήρες |
| Κείμενο | 9 | Χρησιμοποιεί κωδικοποίηση Text. Κωδικοποιεί αλφαριθμητικούς πεζούς, κεφαλαίους και ειδικούς χαρακτήρες |
| EDIFACT | 10 | Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία, κεφαλαία γράμματα και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζά γράμματα. |
| ANSIX12 | 11 | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
| Εκτεταμένο | 13 |  |
| Base256 | 14 | Κωδικοποίηση τιμών 8 bit |
| Δυαδικό | 15 | Σε δυαδική λειτουργία, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | 16 | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που καθορίζεται από το ECIEncoding με την εισαγωγή ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλαιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |

## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να κάνετε codetext σε Εκτεταμένη Λειτουργία.
```cpp
[C#]
//Λειτουργία Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Λειτουργία Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Λειτουργία εκτεταμένου κειμένου κώδικα
//δημιουργία κειμένου κώδικα
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//δημιουργία κειμένου κώδικα
string codetext = textBuilder.GetExtendedCodetext();

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

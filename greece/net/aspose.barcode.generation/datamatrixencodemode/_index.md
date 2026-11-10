---
title: "Enum DataMatrixEncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. Η λειτουργία κωδικοποίησης DataMatrix προεπιλογή είναι Auto"
type: docs
weight: 1200
url: /el/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

Λειτουργία κωδικοποίησης του κωδικοποιητή DataMatrix, προεπιλογή Auto

```csharp
public enum DataMatrixEncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται ξανά στην κωδικοποίηση που ορίζεται από το ECIEncoding με την προσθήκη ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. |
| ASCII | `1` | Κωδικοποιεί έναν αλφαριθμητικό ή δύο αριθμητικούς χαρακτήρες ανά byte |
| C40 | `8` | Χρησιμοποιεί κωδικοποίηση C40. Κωδικοποιεί αλφαριθμητικούς σε κεφαλαία, πεζά και ειδικούς χαρακτήρες. |
| Text | `9` | Χρησιμοποιεί κωδικοποίηση Text. Κωδικοποιεί αλφαριθμητικούς σε πεζά, κεφαλαία και ειδικούς χαρακτήρες. |
| EDIFACT | `10` | Χρησιμοποιεί κωδικοποίηση EDIFACT. Χρησιμοποιεί έξι bits ανά χαρακτήρα, κωδικοποιεί ψηφία, κεφαλαία γράμματα και πολλά σημεία στίξης, αλλά δεν υποστηρίζει πεζά γράμματα. |
| ANSIX12 | `11` | Χρησιμοποιεί κωδικοποίηση ANSI X12. |
| Extended | `13` | Η λειτουργία ExtendedCodetext επιτρέπει την χειροκίνητη εναλλαγή σχημάτων κωδικοποίησης και κωδικοποιήσεων ECI στο codetext. |
| Base256 | `14` | Κωδικοποίηση τιμών 8 bit |
| Binary | `15` | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | `16` | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που ορίζεται από το ECIEncoding με την προσθήκη ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε codetext σε λειτουργία Extended.

```csharp
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


//Λειτουργία Extended codetext
//δημιουργία codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



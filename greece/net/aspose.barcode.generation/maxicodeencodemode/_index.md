---
title: "Απαρίθμηση MaxiCodeEncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.Generation.MaxiCodeEncodeMode. Λειτουργία κωδικοποίησης για barcodes MaxiCode"
type: docs
weight: 1460
url: /el/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

Λειτουργία κωδικοποίησης για γραμμωτούς κώδικες MaxiCode.

```csharp
public enum MaxiCodeEncodeMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Auto | `0` | Σε λειτουργία Auto, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Οι χαρακτήρες Unicode κωδικοποιούνται ξανά στην κωδικοποίηση που ορίζεται από το ECIEncoding με την προσθήκη ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. |
| Extended | `3` | Εκτεταμένη λειτουργία που υποστηρίζει πολλαπλές λειτουργίες ECI. |
| Binary | `4` | Σε λειτουργία Binary, το CodeText κωδικοποιείται με μέγιστη συμπίεση δεδομένων. Εάν βρεθεί χαρακτήρας Unicode, ρίχνεται εξαίρεση. |
| ECI | `5` | Σε λειτουργία ECI, ολόκληρο το μήνυμα κωδικοποιείται ξανά στην κωδικοποίηση που ορίζεται από το ECIEncoding με την προσθήκη ενός αναγνωριστικού ECI. Εάν βρεθεί χαρακτήρας που δεν υποστηρίζεται από την επιλεγμένη κωδικοποίηση ECI, ρίχνεται εξαίρεση. Παρακαλούμε σημειώστε ότι ορισμένα παλιά (πριν το 2006) σαρωτές ενδέχεται να μην υποστηρίζουν αυτή τη λειτουργία. |

## Παραδείγματα

```csharp
[C#]
//Λειτουργία Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Λειτουργία Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Λειτουργία Extended codetext
//δημιουργία codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//παραγωγή codetext
string codetext = textBuilder.GetExtendedCodetext();    

//δημιουργία
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



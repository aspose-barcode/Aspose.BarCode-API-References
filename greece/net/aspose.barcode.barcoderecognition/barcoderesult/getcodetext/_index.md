---
title: "BarCodeResult.GetCodeText"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarCodeResult μέθοδος. Λαμβάνει το κείμενο κώδικα με κωδικοποίηση"
type: docs
weight: 130
url: /el/net/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult.GetCodeText method

Λαμβάνει το κείμενο κώδικα με κωδικοποίηση.

```csharp
public string GetCodeText(Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικοποίηση | Κωδικοποίηση | Η κωδικοποίηση για το κείμενο κώδικα. |

### Τιμή Επιστροφής

Μια συμβολοσειρά που περιέχει το αναγνωρισμένο κείμενο κώδικα.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το `GetCodeText`:

```csharp
[C#]
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    gen.SetCodeText("車種名", Encoding.GetEncoding(932));
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

### Δείτε επίσης

* class [BarCodeResult](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



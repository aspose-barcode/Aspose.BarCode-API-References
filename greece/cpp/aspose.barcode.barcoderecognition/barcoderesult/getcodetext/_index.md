---
title: "μέθοδος"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Λαμβάνει το κείμενο κώδικα με κωδικοποίηση σε C++."
type: docs
weight: 1000
url: /el/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


Λαμβάνει το κείμενο του κώδικα με κωδικοποίηση.

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κωδικοποίηση | System::SharedPtr\\<System::Text::Encoding\\> | Η κωδικοποίηση για το κείμενο κώδικα. |

### ReturnValue

Μια συμβολοσειρά που περιέχει το αναγνωρισμένο κείμενο κώδικα.
## Σχόλια



Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε **GetCodeText**:


```cpp
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

## Δείτε επίσης

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "μέθοδος"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Ορίζει το codetext ως ακολουθία byte σε C++."
type: docs
weight: 700
url: /el/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Ορίστε το codetext ως ακολουθία byte.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Byte του codetext |

## Δείτε επίσης

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeText | System::String | Συμβολοσειρά CodeText |
| κωδικοποίηση | System::SharedPtr\\<System::Text::Encoding\\> | Εφαρμοσμένη κωδικοποίηση |
## Σχόλια


Κωδικοποιεί το Unicode **codeText** σε μια ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο συχνά χρησιμοποιούμενη κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει, η συνάρτηση εισάγει αυτόματα ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Αυτή η συνάρτηση προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει τη χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη στις σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) για δεδομένα Unicode.

Η χρήση αυτής της συνάρτησης με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων των 2D), ή HIBC barcode (συμπεριλαμβανομένων των 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το **SetCodeText** για ορισμό κειμένου κωδικοποιημένου σε Unicode για 2D barcode χρησιμοποιώντας διαφορετικές κωδικοποιήσεις:


```cpp
[C#]
//Κωδικοποίηση κειμένου QR Code χρησιμοποιώντας UTF-8 με BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Κωδικοποίηση κειμένου DataMatrix χρησιμοποιώντας Shift-JIS (Ιαπωνική κωδικοποίηση)
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

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeText | System::String | Συμβολοσειρά CodeText |
| κωδικοποίηση | System::SharedPtr\\<System::Text::Encoding\\> | Εφαρμοσμένη κωδικοποίηση |
| insertBOM | bool | Δηλώνει εάν θα εισαχθεί ένα byte order mark (BOM) όταν η καθορισμένη κωδικοποίηση το υποστηρίζει (π.χ., UTF-8, UTF-16, UTF-32). Εάν οριστεί σε **true**, το BOM προστίθεται· εάν σε **false**, το BOM παραλείπεται ακόμη και αν η κωδικοποίηση το χρησιμοποιεί συνήθως. |
## Σχόλια


Κωδικοποιεί το Unicode **codeText** σε μια ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο συχνά χρησιμοποιούμενη κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει και το **insertBOM** οριστεί σε **true**, η συνάρτηση περιλαμβάνει ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Αυτή η συνάρτηση προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει τη χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη στις σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) για δεδομένα Unicode.

Η χρήση αυτής της συνάρτησης με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων των 2D), ή HIBC barcode (συμπεριλαμβανομένων των 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.


Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το **SetCodeText** με ή χωρίς BOM για 2D barcode.


```cpp
[C#]
    //Κωδικοποιήστε το κείμενο κώδικα χρησιμοποιώντας UTF-8 με BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Κωδικοποιήστε το κείμενο κώδικα χρησιμοποιώντας UTF-8 χωρίς BOM
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Δείτε επίσης

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

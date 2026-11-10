---
title: "BarcodeGenerator.SetCodeText"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "BarcodeGenerator μέθοδος. Ορίζει το κείμενο κώδικα ως ακολουθία bytes"
type: docs
weight: 100
url: /el/net/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## SetCodeText(byte[]) {#setcodetext}

Ορίζει το codetext ως ακολουθία byte.

```csharp
public void SetCodeText(byte[] codeBytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeBytes | Byte[] | Bytes του κειμένου κώδικα |

### Δείτε επίσης

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding) {#setcodetext_1}

Κωδικοποιεί το Unicode **codeText** σε ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο κοινή κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει, η λειτουργία εισάγει αυτόματα ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Αυτή η λειτουργία προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει την χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη σε σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) για δεδομένα Unicode.

Η χρήση αυτής της λειτουργίας με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων των 2D) ή barcode HIBC (συμπεριλαμβανομένων των 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.

```csharp
public void SetCodeText(string codeText, Encoding encoding)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeText | String | CodeText συμβολοσειρά |
| κωδικοποίηση | Κωδικοποίηση | Εφαρμοσμένη κωδικοποίηση |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το `SetCodeText` για ορισμό κειμένου κωδικοποιημένου σε Unicode για 2D barcode χρησιμοποιώντας διαφορετικές κωδικοποιήσεις:

```csharp
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

### Δείτε επίσης

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)

---

## SetCodeText(string, Encoding, bool) {#setcodetext_2}

Κωδικοποιεί το Unicode **codeText** σε ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο κοινή κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει και το **insertBOM** είναι ορισμένο σε `true`, η λειτουργία περιλαμβάνει ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding).

Αυτή η λειτουργία προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει την χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη σε σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις χρήσης, συνιστάται η κωδικοποίηση [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) για δεδομένα Unicode.

Η χρήση αυτής της λειτουργίας με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων των 2D) ή barcode HIBC (συμπεριλαμβανομένων των 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα.

```csharp
public void SetCodeText(string codeText, Encoding encoding, bool insertBOM)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| codeText | String | CodeText συμβολοσειρά |
| κωδικοποίηση | Κωδικοποίηση | Εφαρμοσμένη κωδικοποίηση |
| insertBOM | Boolean | Δηλώνει εάν θα εισαχθεί ένα byte order mark (BOM) όταν η καθορισμένη κωδικοποίηση το υποστηρίζει (π.χ., UTF-8, UTF-16, UTF-32). Εάν οριστεί σε `true`, το BOM προστίθεται· εάν σε `false`, το BOM παραλείπεται ακόμη και αν η κωδικοποίηση το χρησιμοποιεί συνήθως. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το `SetCodeText` με ή χωρίς BOM για 2D barcode.

```csharp
[C#]
//Κωδικοποίηση κειμένου codetext χρησιμοποιώντας UTF-8 με BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, true);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Κωδικοποίηση κειμένου codetext χρησιμοποιώντας UTF-8 χωρίς BOM
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8, false);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

### Δείτε επίσης

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)



---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeResult κλάση"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeResult κλάση. Αποθηκεύει τα αναγνωρισμένα δεδομένα barcode όπως τύπο SingleDecodeType, System::String codetext, BarCodeRegionParameters region και άλλες παραμέτρους σε C++."
type: docs
weight: 700
url: /el/cpp/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class


Αποθηκεύει τα αναγνωρισμένα δεδομένα barcode όπως τύπο [SingleDecodeType](../singledecodetype/), **System::String** codetext, [BarCodeRegionParameters](../barcoderegionparameters/) region και άλλες παραμέτρους.

```cpp
class BarCodeResult : public System::ICloneable,
                      public System::IEquatable<System::SharedPtr<BarCodeResult>>
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [BarCodeResult](./barcoderesult/)(System::SharedPtr\<BarCodeResult\>) | Δημιουργεί ένα αντίγραφο της κλάσης [BarCodeResult](./). |
| [Clone](./clone/)() override | Δημιουργεί ένα αντίγραφο της κλάσης [BarCodeResult](./). |
| [Equals](./equals/)(System::SharedPtr\<BarCodeResult\>) override | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή [BarCodeResult](./). |
| [get_CodeBytes](./get_codebytes/)() const | Λαμβάνει τα κωδικοποιημένα bytes του κώδικα. |
| [get_CodeText](./get_codetext/)() const | Λαμβάνει το κείμενο του κώδικα. |
| [get_CodeType](./get_codetype/)() const | Λαμβάνει τον τύπο barcode. |
| [get_CodeTypeName](./get_codetypename/)() | Λαμβάνει το όνομα του τύπου barcode. |
| [get_Confidence](./get_confidence/)() const | Λαμβάνει το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode. |
| [get_Extended](./get_extended/)() const | Λαμβάνει τις εκτεταμένες παραμέτρους του αναγνωρισμένου barcode. |
| [get_IsoSymbolQuality](./get_isosymbolquality/)() const | Λαμβάνει τα αποτελέσματα αξιολόγησης ποιότητας συμβόλου ISO/IEC για το αναγνωρισμένο barcode. |
| [get_ReadingQuality](./get_readingquality/)() const | Λαμβάνει την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικά barcode. |
| [get_Region](./get_region/)() const | Λαμβάνει την περιοχή barcode. |
| [GetCodeText](./getcodetext/)(System::SharedPtr\<System::Text::Encoding\>) | Λαμβάνει το κείμενο του κώδικα με κωδικοποίηση. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του [BarCodeResult](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να αποκτήσετε το [BarCodeResult](./).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "μέθοδος"
linktitle: "set_IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " μέθοδος. Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο Πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση ως μέθοδος CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία \"333\" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα \"z\" σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.barcoderecognition/australiapostsettings/set_ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable method


Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοήσει τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία "333" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα "z".

```cpp
void Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings::set_IgnoreEndingFillingPatternsForCTable(bool value)
```

## Σχόλια


Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος κατά την αποκωδικοποίηση με τη μέθοδο CTable

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε το barcode Australia Post με Τύπο Ερμηνείας CTable και αγνοώντας τα μοτίβα γεμίσματος.
```cpp
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678AB")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            reader.BarcodeSettings.AustraliaPost.IgnoreEndingFillingPatternsForCTable = True
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## Δείτε επίσης

* Class [AustraliaPostSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα AustraliaPostSettings. Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο πεδίο Πληροφορίες Πελάτη κατά την αποκωδικοποίηση με τη μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία 333 των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα z."
type: docs
weight: 30
url: /el/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος στο Πεδίο Πληροφοριών Πελάτη κατά την αποκωδικοποίηση ως μέθοδο CTable. Η μέθοδος κωδικοποίησης CTable δεν έχει κενά στον πίνακα κωδικοποίησης και η ακολουθία "333" των μοτίβων γεμίσματος αποκωδικοποιείται ως το γράμμα "z".

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

Η σημαία που αναγκάζει τον αποκωδικοποιητή AustraliaPost να αγνοεί τα τελευταία μοτίβα γεμίσματος κατά την αποκωδικοποίηση με τη μέθοδο CTable.

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε γραμμωτό κώδικα Australia Post με τύπο ερμηνείας CTable και αγνοώντας τα μοτίβα γεμίσματος.

```csharp
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

### Δείτε επίσης

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



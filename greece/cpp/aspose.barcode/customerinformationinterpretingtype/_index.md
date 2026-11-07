---
title: "enum"
linktitle: "CustomerInformationInterpretingType"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Ορίζει τον τύπο ερμηνείας (CTable, NTable ή Other) των πληροφοριών πελάτη για το AustralianPost BarCode στο C++."
type: docs
weight: 700
url: /el/cpp/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enum


Ορίζει τον τύπο ερμηνείας (CTable, NTable ή Other) των πληροφοριών πελάτη για το AustralianPost [BarCode](../).

```cpp
enum class CustomerInformationInterpretingType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| CTable | 0 | Χρησιμοποιήστε το CTable για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει A..Z, a..z, 1..9, κενό και το σύμβολο #. |
| NTable | 1 | Χρησιμοποιήστε το NTable για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει ψηφία. |
| Other | 2 | Μην ερμηνεύετε τις πληροφορίες πελάτη. Επιτρέπει μόνο το σύμβολο 0, 1, 2 ή 3. |

## Σχόλια


Αυτά τα παραδείγματα δείχνουν πώς να δημιουργήσετε και να αναγνωρίσετε το barcode της Australia Post.
```cpp
    [C#]
//Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε το barcode της Australia Post με τον τύπο ερμηνείας CTable.
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "5912345678ABCde")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.CTable
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.CTable
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
//Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε το barcode της Australia Post χωρίς τον τύπο Customer Interpreting Type.
    [C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123"))
{
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other;
    using (Bitmap image = generator.GenerateBarCodeImage())
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.AustraliaPost))
     {
        reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other;
        foreach (BarCodeResult result in reader.ReadBarCodes())
        {
            Console.WriteLine("BarCode Type: " + result.CodeType);
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
        }
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.AustraliaPost, "59123456780123012301230123")
    generator.Parameters.Barcode.AustralianPost.AustralianPostEncodingTable = CustomerInformationInterpretingType.Other
    Using image As Bitmap = generator.GenerateBarCodeImage()
        Using reader As New BarCodeReader(image, DecodeType.AustraliaPost)
            reader.BarcodeSettings.AustraliaPost.CustomerInformationInterpretingType = CustomerInformationInterpretingType.Other
            For Each result As BarCodeResult In reader.ReadBarCodes()
                Console.WriteLine("BarCode Type: " + result.CodeTypeName)
                Console.WriteLine("BarCode CodeText: " + result.CodeText)
            Next
        End Using
    End Using
End Using
```

## Δείτε επίσης

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)

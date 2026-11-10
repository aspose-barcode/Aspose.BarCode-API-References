---
title: "Απαρίθμηση CustomerInformationInterpretingType"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.CustomerInformationInterpretingType. Ορίζει τον τύπο ερμηνείας CTable, NTable ή Other για τις πληροφορίες πελάτη του AustralianPost BarCode"
type: docs
weight: 910
url: /el/net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

Ορίζει τον τύπο ερμηνείας (CTable, NTable ή Other) των πληροφοριών πελάτη για το AustralianPost BarCode.

```csharp
public enum CustomerInformationInterpretingType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| CTable | `0` | Χρησιμοποιήστε το CTable για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει A..Z, a..z, 1..9, κενό και το σύμβολο #. |
| NTable | `1` | Χρησιμοποιήστε το NTable για την ερμηνεία των πληροφοριών πελάτη. Επιτρέπει ψηφία. |
| Other | `2` | Μην ερμηνεύετε τις πληροφορίες πελάτη. Επιτρέπει μόνο το σύμβολο 0, 1, 2 ή 3. |

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να δημιουργήσετε και να αναγνωρίσετε το barcode της Australia Post

```csharp
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
//Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αναγνωρίσετε το barcode της Australia Post χωρίς τύπο ερμηνείας πελάτη.
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

### Δείτε επίσης

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)



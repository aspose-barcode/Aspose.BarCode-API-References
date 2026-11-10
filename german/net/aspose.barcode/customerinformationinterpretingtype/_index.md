---
title: "Enum CustomerInformationInterpretingType"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.CustomerInformationInterpretingType Enum. Definiert den Interpretationstyp CTable, NTable oder Other für Kundeninformationen des AustralianPost-Barcodes."
type: docs
weight: 910
url: /de/net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

Definiert den Interpretationstyp (CTable, NTable oder Andere) von Kundeninformationen für den AustralianPost‑Barcode.

```csharp
public enum CustomerInformationInterpretingType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| CTable | `0` | Verwenden Sie CTable, um die Kundeninformationen zu interpretieren. Erlaubt A..Z, a..z, 1..9, Leerzeichen und das #‑Zeichen. |
| NTable | `1` | Verwenden Sie NTable, um die Kundeninformationen zu interpretieren. Erlaubt Ziffern. |
| Other | `2` | Interpretieren Sie die Kundeninformationen nicht. Erlaubt nur das Symbol 0, 1, 2 oder 3. |

## Beispiele

Diese Beispiele zeigen, wie man Australia Post‑Barcodes erzeugt und erkennt.

```csharp
[C#]
//Dieses Beispiel zeigt, wie man Australia Post‑Barcodes mit dem CTable‑Interpretationstyp erzeugt und erkennt.
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
//Dieses Beispiel zeigt, wie man Australia Post‑Barcodes ohne Kundeninterpretationstyp erzeugt und erkennt.
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

### Siehe auch

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)



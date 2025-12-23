---
title: Enum CustomerInformationInterpretingType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.CustomerInformationInterpretingType enum. Defines the interpreting type CTable NTable or Other of customer information for AustralianPost BarCode
type: docs
weight: 810
url: /net/aspose.barcode/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

Defines the interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode.

```csharp
public enum CustomerInformationInterpretingType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| CTable | `0` | Use CTable to interpret the customer information. Allows A..Z, a..z, 1..9, space and # sign. |
| NTable | `1` | Use NTable to interpret the customer information. Allows digits. |
| Other | `2` | Do not interpret the customer information. Allows 0, 1, 2 or 3 symbol only. |

## Examples

These samples show how to generate and recognize Australia Post barcode

```csharp
[C#]
//This sample shows how to generate and recognize Australia Post barcode with CTable Interpreting Type.
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
//This sample shows how to generate and recognize Australia Post barcode without Customer Interpreting Type.
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

### See Also

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)



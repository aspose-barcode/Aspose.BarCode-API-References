---
title: "AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "AustraliaPostSettings-Eigenschaft. Das Flag, das den AustraliaPost-Dekodierer zwingt, die letzten Füllmuster im Kundeninformationsfeld während der Dekodierung mit der CTable-Methode zu ignorieren. Die CTable-Codierungsmethode hat keine Lücken in der Codierungstabelle und die Sequenz 333 der Füllmuster wird als Buchstabe z dekodiert"
type: docs
weight: 30
url: /de/net/aspose.barcode.barcoderecognition/australiapostsettings/ignoreendingfillingpatternsforctable/
---
## AustraliaPostSettings.IgnoreEndingFillingPatternsForCTable property

Das Flag, das den AustraliaPost-Dekodierer zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung nach der CTable-Methode zu ignorieren. Die CTable-Kodierungsmethode hat keine Lücken in der Kodierungstabelle und die Sequenz "333" von Füllmustern wird als Buchstabe "z" dekodiert.

```csharp
public bool IgnoreEndingFillingPatternsForCTable { get; set; }
```

### Property Value

Das Flag, das den AustraliaPost-Dekodierer zwingt, die letzten Füllmuster während der CTable-Methoden-Dekodierung zu ignorieren

## Beispiele

Dieses Beispiel zeigt, wie man einen Australia Post-Barcode mit CTable-Interpretations-Typ erzeugt und erkennt, wobei Füllmuster ignoriert werden.

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

### Siehe auch

* class [AustraliaPostSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



---
title: DetectEncoding
second_title: Aspose.BarCode för .NET API-referens
description: Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-koduppsättningar. Standardvärdet är sant.
type: docs
weight: 30
url: /sv/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-koduppsättningar. Standardvärdet är sant.

```csharp
public bool DetectEncoding { get; set; }
```

### Fastighetsvärde

Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-koduppsättningar

### Exempel

Det här exemplet visar hur man upptäcker textkodning i farten om DetectEncoding är aktiverat

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
    {
        generator.Parameters.Barcode.QR.CodeTextEncoding = Encoding.UTF8;
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //detekterar kodning för Unicode-koduppsättningar är aktiverad
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //detect encoding är inaktiverat
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.Parameters.Barcode.QR.CodeTextEncoding = System.Text.Encoding.UTF8
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'upptäcker kodning för Unicode-koduppsättningar är aktiverad
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detektera kodning är inaktiverad
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Se även

* class [BarcodeSettings](../../barcodesettings)
* namnutrymme [Aspose.BarCode.BarCodeRecognition](../../barcodesettings)
* hopsättning [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
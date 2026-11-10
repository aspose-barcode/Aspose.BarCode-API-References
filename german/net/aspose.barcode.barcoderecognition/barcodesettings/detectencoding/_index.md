---
title: "BarcodeSettings.DetectEncoding"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeSettings Eigenschaft. Das Flag, das die Engine zwingt, die Codetext‑Kodierung für Unicode‑Zeichensätze zu erkennen. Der Standardwert ist true"
type: docs
weight: 40
url: /de/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

Die Flagge, die die Engine zwingt, die Codetextkodierung für Unicode-Zeichensätze zu erkennen. Standardwert ist true.

```csharp
public bool DetectEncoding { get; set; }
```

### Property Value

Das Flag, das die Engine zwingt, die Codetext‑Kodierung für Unicode‑Zeichensätze zu erkennen

## Beispiele

Dieses Beispiel zeigt, wie die Textekodierung dynamisch erkannt wird, wenn DetectEncoding aktiviert ist

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //Erkennung der Kodierung für Unicode‑Zeichensätze ist aktiviert
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //Kodierungserkennung ist deaktiviert
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
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### Siehe auch

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



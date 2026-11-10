---
title: "BarcodeSettings.StripFNC"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "BarcodeSettings Eigenschaft. Entfernt FNC1‑, FNC2‑ und FNC3‑Zeichen aus dem Codetext. Der Standardwert ist false"
type: docs
weight: 60
url: /de/net/aspose.barcode.barcoderecognition/barcodesettings/stripfnc/
---
## BarcodeSettings.StripFNC property

Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false.

```csharp
public bool StripFNC { get; set; }
```

### Property Value

Entfernt FNC1-, FNC2- und FNC3-Zeichen aus dem Codetext. Standardwert ist false.

## Beispiele

Dieses Beispiel zeigt, wie FNC‑Zeichen entfernt werden

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC deaktiviert
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC aktiviert
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC disabled
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC enabled
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Siehe auch

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



---
title: "metod"
linktitle: "get_DetectEncoding"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är sant i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_detectencoding/
---
## BarcodeSettings::get_DetectEncoding method


Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är true.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_DetectEncoding() const
```

## Anmärkningar


Det här exemplet visar hur man upptäcker textkodning i farten om DetectEncoding är aktiverad
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //detekterar kodning för Unicode-teckenuppsättningar är aktiverad
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //detektera kodning är inaktiverad
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


Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar
## Se även

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

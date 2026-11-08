---
title: "metod"
linktitle: "set_StripFNC"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ta bort FNC1-, FNC2- och FNC3‑tecken från kodtexten. Standardvärdet är false i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_stripfnc/
---
## BarcodeSettings::set_StripFNC method


Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_StripFNC(bool value)
```

## Anmärkningar


Det här exemplet visar hur man tar bort FNC-tecken
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC inaktiverad
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC aktiverad
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


Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false.
## Se även

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

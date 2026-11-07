---
title: "method"
linktitle: "get_StripFNC"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Удалять символы FNC1, FNC2, FNC3 из кода. Значение по умолчанию — false в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_stripfnc/
---
## BarcodeSettings::get_StripFNC method


Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_StripFNC() const
```

## Примечания


Этот пример показывает, как удалять символы FNC
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC отключён
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC включён
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


Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false.
## См. также

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

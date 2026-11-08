---
title: "método"
linktitle: "get_StripFNC"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Elimina los caracteres FNC1, FNC2, FNC3 del texto codificado. El valor predeterminado es false en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_stripfnc/
---
## BarcodeSettings::get_StripFNC method


Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_StripFNC() const
```

## Observaciones


Este ejemplo muestra cómo eliminar los caracteres FNC
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC deshabilitado
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC habilitado
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


Elimina los caracteres FNC1, FNC2, FNC3 del texto del código. El valor predeterminado es false.
## Ver también

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

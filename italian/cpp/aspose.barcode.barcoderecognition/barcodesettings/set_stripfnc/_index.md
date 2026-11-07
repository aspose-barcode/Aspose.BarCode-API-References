---
title: "method"
linktitle: "set_StripFNC"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Rimuove i caratteri FNC1, FNC2, FNC3 dal codetext. Il valore predefinito è false in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_stripfnc/
---
## BarcodeSettings::set_StripFNC method


Rimuove i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_StripFNC(bool value)
```

## Osservazioni


Questo esempio mostra come rimuovere i caratteri FNC
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC disabilitato
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC abilitato
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


Rimuove i caratteri FNC1, FNC2, FNC3 dal testo del codice. Il valore predefinito è false.
## Vedi anche

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

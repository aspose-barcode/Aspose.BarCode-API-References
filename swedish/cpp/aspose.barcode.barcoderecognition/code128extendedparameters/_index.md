---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. Lagrar speciella data för Code128 igenkänd streckkod i C++."
type: docs
weight: 1300
url: /sv/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Lagrar speciella data för avläst Code128-streckkod

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Hämtar [Code128DataPortion](../code128dataportion/) array av igenkänd Code128-streckkod |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [Code128ExtendedParameters](./). |
## Anmärkningar


Representerar den avlästa streckkodens region och streckkodsvinkel

Detta exempel visar hur man får råvärden för code128
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

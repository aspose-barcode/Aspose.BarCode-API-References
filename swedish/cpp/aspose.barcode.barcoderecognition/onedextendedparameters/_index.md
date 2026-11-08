---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters klass"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters klass. Lagrar speciella data för 1D‑erkända streckkoder, såsom separat kodtext och kontrollsumma i C++."
type: docs
weight: 2700
url: /sv/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Lagrar speciella data för 1D-igenkänd streckkod, såsom separat kodtext och kontrollsumma.

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | Hämtar kontrollsumman för 1D‑streckkoder. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [get_Value](./get_value/)() const | Hämtar kodtexten för 1D‑streckkoder utan kontrollsumma. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [OneDExtendedParameters](./). |
## Anmärkningar


Detta exempel visar hur man hämtar 1D‑streckkodsvärde och kontrollsumma
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

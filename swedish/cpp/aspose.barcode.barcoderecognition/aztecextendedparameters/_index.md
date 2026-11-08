---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Lagrar speciella data för Aztec igenkänd streckkod i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Lagrar speciella data för Aztec-avläst streckkod

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Hämtar ID för Aztec structured append-lägesstreckkoden. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Hämtar antalet Aztec structured append-lägesstreckkoder. Standardvärdet är 0. Antalet måste vara ett värde mellan 1 och 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Hämtar fil-ID för Aztec structured append-läget. Standardvärdet är en tom sträng |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [AztecExtendedParameters](./). |
## Anmärkningar


Detta exempel visar hur man får Aztec råvärden
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

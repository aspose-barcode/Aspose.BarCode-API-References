---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Slaat speciale gegevens van de herkende Aztec‑barcode op in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Slaat speciale gegevens op van de herkende Aztec-barcode

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Haalt de ID op van de Aztec structured append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Haalt het aantal barcodes op van de Aztec structured append-modus. Standaardwaarde is 0. Het aantal moet een waarde tussen 1 en 26 zijn. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Haalt de bestands-ID op van de Aztec structured append-modus. Standaardwaarde is een lege tekenreeks |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [AztecExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld toont hoe u ruwe Aztec-waarden kunt ophalen
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

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters klasse"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters klasse. Slaat speciale gegevens op van de herkende DotCode-barcode in C++."
type: docs
weight: 2000
url: /nl/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Slaat speciale gegevens op van de herkende DotCode‑barcode

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Haalt de ID op van de DotCode gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Haalt het aantal barcodes op van de DotCode gestructureerde append-modus. Standaardwaarde is -1. Het aantal moet een waarde zijn van 1 tot 35. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld toont hoe je de ruwe waarden van DotCode kunt ophalen
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters klasse"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters klasse. Slaat speciale gegevens op van de herkende DataMatrix-barcode in C++."
type: docs
weight: 1500
url: /nl/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Slaat speciale gegevens op van de herkende [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) barcode

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Haalt de ID op van de [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Haalt het aantal barcodes op van de [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) gestructureerde append-modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Haalt de ID op van de [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) gestructureerde append-modus barcode. ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DataMatrixExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld toont hoe u de ruwe waarden van [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) kunt ophalen
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

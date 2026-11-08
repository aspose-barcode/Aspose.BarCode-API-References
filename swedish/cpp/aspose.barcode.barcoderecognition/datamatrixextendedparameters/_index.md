---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters klass"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters klass. Lagrar speciella data för den igenkända DataMatrix-streckkoden i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Lagrar speciella data för den igenkända [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) streckkoden

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Anger om koden används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Hämtar ID för den [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) strukturerade append-lägesstreckkoden. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Hämtar antalet [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) streckkoder i strukturerat append-läge. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Hämtar ID för den [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) strukturerade append-lägesstreckkoden. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [DataMatrixExtendedParameters](./). |
## Anmärkningar


Detta exempel visar hur man får de råa värdena för [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)
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

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

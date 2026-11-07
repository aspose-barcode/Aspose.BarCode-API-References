---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters Klasse"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters Klasse. Speichert spezielle Daten des erkannten DataMatrix-Barcodes in C++."
type: docs
weight: 1500
url: /de/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


Speichert spezielle Daten des erkannten [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) Barcodes

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Ruft die ID des [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) Structured-Append‑Barcodes ab. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Ruft die Anzahl der [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) Structured-Append‑Barcodes ab. Der Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Ruft die ID des [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) Structured-Append‑Barcodes ab. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist -1. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DataMatrixExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man die Rohwerte von [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) erhält
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

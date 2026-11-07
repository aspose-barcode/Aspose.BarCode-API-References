---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. Speichert spezielle Daten des erkannten Aztec-Barcodes in C++."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Speichert spezielle Daten des erkannten Aztec-Barcode

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Ruft die ID des Aztec Structured Append‑Modus‑Barcodes ab. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Der Standardwert ist 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Ruft die Anzahl der Aztec Structured Append‑Modus‑Barcodes ab. Der Standardwert ist 0. Die Anzahl muss ein Wert zwischen 1 und 26 sein. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Ermittelt die Datei-ID des Aztec-Structured-Append-Modus. Der Standardwert ist eine leere Zeichenkette. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [AztecExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man rohe Aztec‑Werte erhält.
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

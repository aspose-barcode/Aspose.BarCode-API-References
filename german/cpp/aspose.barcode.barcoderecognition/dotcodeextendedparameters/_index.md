---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters Klasse"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters Klasse. Speichert spezielle Daten des erkannten DotCode-Strichcodes in C++."
type: docs
weight: 2000
url: /de/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


Speichert spezielle Daten des erkannten DotCode-Barcodes

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Ermittelt die ID des DotCode Structured Append Mode Strichcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Anzahl der Strichcodes sein. Standardwert ist -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Ermittelt die Anzahl der DotCode Structured Append Mode Strichcodes. Standardwert ist -1. Die Anzahl muss ein Wert zwischen 1 und 35 sein. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DotCodeExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man rohe DotCode-Werte erhält
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

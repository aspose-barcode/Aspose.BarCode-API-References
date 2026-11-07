---
title: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters class. Speichert spezielle Daten des erkannten Code128-Barcodes in C++."
type: docs
weight: 1300
url: /de/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


Speichert spezielle Daten des erkannten Code128-Barcodes

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | Ruft das [Code128DataPortion](../code128dataportion/)-Array des erkannten Code128-Barcodes ab |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [Code128ExtendedParameters](./) zurück |
## Hinweise


Stellt die Region des erkannten Barcodes und den Barcode-Winkel dar

Dieses Beispiel zeigt, wie man rohe Code128-Werte erhält
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters Klasse"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters Klasse. Speichert spezielle Daten des erkannten 1D‑Barcodes, wie getrennten Codetext und Prüfsumme, in C++."
type: docs
weight: 2700
url: /de/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


Speichert spezielle Daten des erkannten 1D‑Barcodes, wie separaten Codetext und Prüfsumme.

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | Liefert die Prüfsumme für 1D‑Barcodes. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_Value](./get_value/)() const | Liefert den Codetext von 1D‑Barcodes ohne Prüfsumme. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [OneDExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie der Wert und die Prüfsumme eines 1D‑Barcodes abgerufen werden.
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

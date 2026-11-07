---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters Klasse"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters Klasse. Speichert zusätzliche DataBar-Informationen des erkannten Barcodes in C++."
type: docs
weight: 1400
url: /de/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Speichert zusätzliche Informationen eines DataBar des erkannten Barcodes

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | Liest das DataBar 2D Composite-Komponenten-Flag. Standardwert ist false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DataBarExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man zusätzliche DataBar-Informationen erhält.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

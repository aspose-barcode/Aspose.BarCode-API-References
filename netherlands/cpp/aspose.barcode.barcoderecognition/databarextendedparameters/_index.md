---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters klasse"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class. Slaat extra DataBar‑informatie van de herkende barcode op in C++."
type: docs
weight: 1400
url: /nl/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Slaat aanvullende informatie van DataBar op voor de herkende barcode

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | Haalt de DataBar 2D‑composite‑componentvlag op. Standaardwaarde is false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit [DataBarExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld laat zien hoe extra DataBar‑informatie te verkrijgen.
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

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

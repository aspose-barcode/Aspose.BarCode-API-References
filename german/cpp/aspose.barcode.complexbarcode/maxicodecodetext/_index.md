---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext Klasse"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext Klasse. Basisklasse zum Kodieren und Dekodieren des im MaxiCode-Code eingebetteten Textes in C++."
type: docs
weight: 1600
url: /de/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Basisklasse zum Codieren und Dekodieren des im MaxiCode-Code eingebetteten Textes.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Ruft die ECI-Codierung ab. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Ruft einen MaxiCode-Codierungsmodus ab. Standardwert: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Liest den Barcode-Typ. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Erstellt Codetext |
| virtual [GetMode](./getmode/)() const | Ruft den MaxiCode-Modus ab. |
| virtual [InitFromString](./initfromstring/)(System::String) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto. |
## Hinweise


Dieses Beispiel zeigt, wie man rohen MaxiCode-Codetext in eine [MaxiCodeCodetext](./)-Instanz dekodiert.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

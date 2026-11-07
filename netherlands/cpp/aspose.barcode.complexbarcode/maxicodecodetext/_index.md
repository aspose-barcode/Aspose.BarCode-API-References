---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext class. Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de MaxiCode-code in C++."
type: docs
weight: 1600
url: /nl/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Basisklasse voor het coderen en decoderen van de in de MaxiCode-code ingebedde tekst.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Haalt een MaxiCode-codemodus op. Standaardwaarde: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Construeert codetext |
| virtual [GetMode](./getmode/)() const | Haalt MaxiCode-modus op. |
| virtual [InitFromString](./initfromstring/)(System::String) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Stelt een MaxiCode-codemodus in. Standaardwaarde: Auto. |
## Opmerkingen


Dit voorbeeld toont hoe ruwe MaxiCode-codetekst te decoderen naar een [MaxiCodeCodetext](./)-instantie.
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

## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

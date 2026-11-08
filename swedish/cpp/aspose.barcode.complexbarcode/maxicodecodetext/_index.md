---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext klass"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext klass. Basklass för kodning och avkodning av texten som är inbäddad i MaxiCode-koden i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


Basklass för kodning och avkodning av texten som är inbäddad i MaxiCode-koden.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstyp. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Konstruerar kodtext |
| virtual [GetMode](./getmode/)() const | Hämtar MaxiCode-läge. |
| virtual [InitFromString](./initfromstring/)(System::String) | Initierar objektet från konstruerad kodtext. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto. |
## Anmärkningar


Detta exempel visar hur man avkodar rå MaxiCode-kodtext till en [MaxiCodeCodetext](./) instans.
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

## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

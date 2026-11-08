---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext klass"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext klass. Klass för kodning och avkodning av MaxiCode‑kodtext för lägena 4, 5 och 6 i C++."
type: docs
weight: 2000
url: /sv/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Klass för kodning och avkodning av MaxiCode-kodtext för lägena 4, 5 och 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [MaxiCodeStandardCodetext](./)‑värde. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Hämtar ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Hämtar ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [get_Message](./get_message/)() const | Hämtar meddelande. |
| [get_Mode](./get_mode/)() | Hämtar MaxiCode‑läge. Standardkodtext kan endast användas med lägena 4, 5 och 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetMode](./getmode/)() const override | Hämtar MaxiCode-läge. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Ställer in ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Ställer in ett MaxiCode-kodningsläge. Standardvärde: Auto. |
| [set_Message](./set_message/)(System::String) | Ställer in meddelande. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Ställer in MaxiCode‑läge. Standardkodtext kan endast användas med lägena 4, 5 och 6. |
## Anmärkningar


//Läge 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Testmeddelande"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Läge 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Testmeddelande"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Läge 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Testmeddelande"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Se även

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

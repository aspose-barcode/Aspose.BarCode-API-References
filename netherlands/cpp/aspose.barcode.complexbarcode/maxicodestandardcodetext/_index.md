---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext klasse"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext klasse. Klasse voor het coderen en decoderen van MaxiCode-codetext voor modus 4, 5 en 6 in C++."
type: docs
weight: 2000
url: /nl/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Klasse voor het coderen en decoderen van MaxiCode-codetekst voor modus 4, 5 en 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde [MaxiCodeStandardCodetext](./) waarde. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Haalt ECI-codering op. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Haalt een MaxiCode-codemodus op. Standaardwaarde: Auto. |
| [get_Message](./get_message/)() const | Haalt bericht op. |
| [get_Mode](./get_mode/)() | Haalt MaxiCode-modus op. Standaard codetext kan alleen worden gebruikt met modus 4, 5 en 6. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetMode](./getmode/)() const override | Haalt MaxiCode-modus op. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer MaxiCodeEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Stelt een MaxiCode-codemodus in. Standaardwaarde: Auto. |
| [set_Message](./set_message/)(System::String) | Stelt bericht in. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Stelt MaxiCode-modus in. Standaard codetext kan alleen worden gebruikt met modus 4, 5 en 6. |
## Opmerkingen


//Modus 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Testbericht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modus 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Testbericht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modus 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Testbericht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Zie ook

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

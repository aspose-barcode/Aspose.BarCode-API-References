---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext Klasse"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext Klasse. Klasse zum Kodieren und Dekodieren von MaxiCode-Codetext für die Modi 4, 5 und 6 in C++."
type: docs
weight: 2000
url: /de/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Klasse zum Codieren und Dekodieren des MaxiCode‑Codetextes für die Modi 4, 5 und 6.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MaxiCodeStandardCodetext](./)-Wert entspricht. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | Ruft die ECI-Codierung ab. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Ruft einen MaxiCode-Codierungsmodus ab. Standardwert: Auto. |
| [get_Message](./get_message/)() const | Liest Nachricht. |
| [get_Mode](./get_mode/)() | Liest MaxiCode-Modus. Standard-Codetext kann nur mit den Modi 4, 5 und 6 verwendet werden. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt Codetext |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetMode](./getmode/)() const override | Ruft den MaxiCode-Modus ab. |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert die Instanz aus dem erstellten Codetext. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto. |
| [set_Message](./set_message/)(System::String) | Setzt Nachricht. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | Setzt MaxiCode-Modus. Standard-Codetext kann nur mit den Modi 4, 5 und 6 verwendet werden. |
## Hinweise


//Modus 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Testnachricht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modus 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Testnachricht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Modus 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Testnachricht"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Siehe auch

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

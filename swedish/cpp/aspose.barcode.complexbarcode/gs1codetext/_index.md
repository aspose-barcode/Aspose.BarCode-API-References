---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext klass"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext klass. Representerar GS1‑kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier‑element. Källordning och upprepade Application Identifier bevaras. Den hakparentes‑representationen har formen (AI)value(AI)value. Ett bokstavligt öppningsparentes ''('' inuti ett värde måste skrivas som (; detta är den enda stödda escape‑sekvensen. Ett avslutningsparentes '')'' inuti ett värde kräver ingen escaping i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Representerar GS1-kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier‑element. Källordningen och upprepade Application Identifier bevaras. Den hakparentes‑representerade formen har formatet (AI)värde(AI)värde. Ett bokstavligt öppningsparentes '(' inom ett värde måste skrivas som (; detta är den enda stödda escape‑sekvensen. Ett avslutningsparentes ')' inom ett värde kräver ingen escape.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Lägger till ett validerat Application Identifier-element. |
| [get_BarcodeType](./get_barcodetype/)() const | Hämtar streckkodstypen som används för att koda denna GS1‑kodtext. Stödda typer är GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR och GS1 DataBar‑typer. Standardvärdet är GS1Code128. |
| [get_Count](./get_count/)() | Hämtar antalet Application Identifier-element. |
| [get_Elements](./get_elements/)() | Hämtar en kopia av alla element i källordning. |
| [GetAll](./getall/)(System::String) | Hämtar alla värden för en Application Identifier i källordning. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstypen som används för att koda denna GS1‑kodtext. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Skapar den hakparentes‑omslutna GS1‑kodtexten i formen (AI)value(AI)value. Bokstavliga öppningsparenteser i värden escapas som (. |
| [GetFirst](./getfirst/)(System::String) | Hämtar det första värdet för en Application Identifier. |
| [GS1Codetext](./gs1codetext/)() | Initierar en tom GS1‑kodtext. |
| [idx_get](./idx_get/)(int32_t) | Hämtar ett element efter dess position i den ordnade sekvensen. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar detta objekt från hakparentes‑omsluten GS1‑kodtext i formen (AI)value(AI)value. Befintliga element ersätts först när den angivna kodtexten har parsats framgångsrikt. |
| static [Parse](./parse/)(System::String) | Parser en hakparentes‑omsluten GS1‑elementsträng i formen (AI)value(AI)value. Ett bokstavligt '(' inuti ett värde måste skrivas som (; ingen annan escape‑sekvens stöds, och ')' kräver ingen escaping. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstypen som används för att koda denna GS1‑kodtext. Stödda typer är GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR och GS1 DataBar‑typer. Standardvärdet är GS1Code128. |
| [ToString](./tostring/)() const override | Returnerar den hakparentesomslutna GS1-representationen i formatet (AI)värde(AI)värde. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Försöker tolka en hakparentesomsluten GS1-elementsträng i formatet (AI)värde(AI)värde och returnerar strukturerade valideringsfel. Ett bokstavligt '(' inuti ett värde måste skrivas som (; ingen annan escape‑sekvens stöds, och ')' kräver ingen escaping. |
| static [Validate](./validate/)(System::String) | Validerar en hakparentesomsluten GS1-elementsträng i formatet (AI)värde(AI)värde utan att konstruera ett objekt. Ett bokstavligt '(' inuti ett värde måste skrivas som (; ingen annan escape‑sekvens stöds, och ')' kräver ingen escaping. |
## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

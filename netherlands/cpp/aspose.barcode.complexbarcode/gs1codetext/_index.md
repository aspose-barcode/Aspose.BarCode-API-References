---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext class"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext class. Vertegenwoordigt GS1-codetekst voor codering en decodering als een geordende reeks Application Identifier‑elementen. Bronvolgorde en herhaalde Application Identifiers worden behouden. De haakjesnotatie heeft de vorm (AI)waarde(AI)waarde. Een letterlijke openingshaak '(' binnen een waarde moet worden geschreven als (; dit is de enige ondersteunde escape‑reeks. Een sluitende haak ')' binnen een waarde hoeft niet te worden geescaped in C++."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Stelt GS1-codetext voor voor codering en decodering als een geordende reeks Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden. De haakjes‑representatie heeft de vorm (AI)waarde(AI)waarde. Een letterlijke openingshaak '(' binnen een waarde moet worden geschreven als (; dit is de enige ondersteunde escape‑reeks. Een sluitingshaak ')' binnen een waarde hoeft niet te worden geescaped.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Voegt een gevalideerd Application Identifier‑element toe. |
| [get_BarcodeType](./get_barcodetype/)() const | Haalt het barcode‑type op dat wordt gebruikt om deze GS1-codetekst te coderen. Ondersteunde types zijn GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR en GS1 DataBar‑types. De standaardwaarde is GS1Code128. |
| [get_Count](./get_count/)() | Haalt het aantal Application Identifier‑elementen op. |
| [get_Elements](./get_elements/)() | Haalt een kopie van alle elementen op in de bronvolgorde. |
| [GetAll](./getall/)(System::String) | Haalt alle waarden op voor een Application Identifier in bronvolgorde. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het barcode‑type op dat wordt gebruikt om deze GS1-codetekst te coderen. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert de haakjes‑GS1‑codetekst in de vorm (AI)waarde(AI)waarde. Letterlijke openingshaakjes in waarden worden geescaped als (. |
| [GetFirst](./getfirst/)(System::String) | Haalt de eerste waarde op voor een Application Identifier. |
| [GS1Codetext](./gs1codetext/)() | Initialiseert een lege GS1-codetekst. |
| [idx_get](./idx_get/)(int32_t) | Haalt een element op op basis van zijn positie in de geordende reeks. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert deze instantie vanuit haakjes‑GS1‑codetekst in de vorm (AI)waarde(AI)waarde. Bestaande elementen worden alleen vervangen nadat de opgegeven codetekst succesvol is geparseerd. |
| static [Parse](./parse/)(System::String) | Parseert een haakjes‑GS1‑elementstring in de vorm (AI)waarde(AI)waarde. Een letterlijke '(' binnen een waarde moet worden geschreven als (; er wordt geen andere escape‑reeks ondersteund, en ')' hoeft niet geescaped te worden. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het barcode‑type in dat wordt gebruikt om deze GS1-codetekst te coderen. Ondersteunde types zijn GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR en GS1 DataBar‑types. De standaardwaarde is GS1Code128. |
| [ToString](./tostring/)() const override | Retourneert de tussen haakjes gegane GS1-representatie in de vorm (AI)waarde(AI)waarde. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Probeert een tussen haakjes gegane GS1-elementreeks te parseren in de vorm (AI)waarde(AI)waarde en retourneert gestructureerde validatiefouten. Een letterlijk '(' binnen een waarde moet worden geschreven als (; er wordt geen andere escape‑reeks ondersteund, en ')' hoeft niet te worden geescaped. |
| static [Validate](./validate/)(System::String) | Valideert een tussen haakjes gegane GS1-elementreeks in de vorm (AI)waarde(AI)waarde zonder een object te construeren. Een letterlijk '(' binnen een waarde moet worden geschreven als (; er wordt geen andere escape‑reeks ondersteund, en ')' hoeft niet te worden geescaped. |
## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

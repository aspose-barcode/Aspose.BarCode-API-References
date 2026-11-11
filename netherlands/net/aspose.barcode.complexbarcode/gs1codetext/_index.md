---
title: "Klas GS1Codetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext class. Vertegenwoordigt GS1-codetext voor codering en decodering als een geordende reeks Application Identifier-elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden. De haakjesweergave heeft de vorm AIvalueAIvalue. Een letterlijke openingshaak '(' binnen een waarde moet worden geschreven als '('; dit is de enige ondersteunde escape‑sequentie. Een sluitingshaak ')' binnen een waarde hoeft niet te worden geescaped."
type: docs
weight: 530
url: /nl/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Stelt GS1-codetekst voor voor codering en decodering als een geordende reeks Application Identifier‑elementen. De oorspronkelijke volgorde en herhaalde Application Identifiers worden behouden. De haakjesweergave heeft de vorm (AI)waarde(AI)waarde. Een letterlijke openingshaak '(' binnen een waarde moet worden geschreven als \(; dit is de enige ondersteunde escape‑reeks. Een sluitingshaak ')' binnen een waarde hoeft niet te worden geescaped.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Haalt of stelt het barcodetype in dat wordt gebruikt om deze GS1-codetext te coderen. Ondersteunde types zijn GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR en GS1 DataBar-types. De standaardwaarde is GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Haalt het aantal Application Identifier-elementen op. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Haalt een kopie van alle elementen op in de oorspronkelijke volgorde. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Haalt een element op basis van zijn positie in de geordende reeks. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Parseert een haakjesgeïntegreerde GS1-elementstring in de vorm (AI)value(AI)value. Een letterlijke '(' binnen een waarde moet worden geschreven als \(; er wordt geen andere escape‑sequentie ondersteund, en ')' hoeft niet te worden geescaped. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Voegt een gevalideerd Application Identifier-element toe. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Haalt alle waarden voor een Application Identifier op in de oorspronkelijke volgorde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Haalt het barcodetype op dat wordt gebruikt om deze GS1-codetext te coderen. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Construeert de tussen haakjes geplaatste GS1-codetekst in de vorm (AI)waarde(AI)waarde. Letterlijke openingshaakjes in waarden worden geescaped als \(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Haalt de eerste waarde voor een Application Identifier op. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Initialiseert deze instantie vanuit tussen haakjes geplaatste GS1-codetekst in de vorm (AI)waarde(AI)waarde. Bestaande elementen worden pas vervangen nadat de opgegeven codetekst succesvol is geparseerd. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Retourneert de tussen haakjes geplaatste GS1-representatie in de vorm (AI)waarde(AI)waarde. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Probeert een tussen haakjes geplaatste GS1-elementstring in de vorm (AI)waarde(AI)waarde te parseren en retourneert gestructureerde validatiefouten. Een letterlijke '(' binnen een waarde moet worden geschreven als \(; geen andere escape‑reeks wordt ondersteund, en ')' hoeft niet te worden geescaped. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Valideert een tussen haakjes geplaatste GS1-elementstring in de vorm (AI)waarde(AI)waarde zonder een object te construeren. Een letterlijke '(' binnen een waarde moet worden geschreven als \(; geen andere escape‑reeks wordt ondersteund, en ')' hoeft niet te worden geescaped. |

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



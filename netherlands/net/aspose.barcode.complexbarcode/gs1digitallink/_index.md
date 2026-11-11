---
title: "Klasse GS1DigitalLink"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.GS1DigitalLink class. Vertegenwoordigt de GS1 Digital Link-codetekst voor codering en decodering als een geordende reeks Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden. De geconstrueerde codetekst is een ongecomprimeerde GS1 Digital Link-URI. Niet‑GS1 query‑parameters en URI‑fragmenten worden genegeerd bij het parseren."
type: docs
weight: 540
url: /nl/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Stelt GS1 Digital Link-codetekst voor voor codering en decodering als een geordende reeks Application Identifier‑elementen. De oorspronkelijke volgorde en herhaalde Application Identifiers worden behouden. De geconstrueerde codetekst is een ongecomprimeerde GS1 Digital Link‑URI. Niet‑GS1 query‑parameters en URI‑fragmenten worden genegeerd bij het parseren.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Initialiseert een lege GS1 Digital Link met de opgegeven URI‑stam. De primaire sleutel wordt automatisch geselecteerd wanneer er precies één kandidaat voor de primaire sleutel aanwezig is. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Initialiseert een lege GS1 Digital Link met de opgegeven URI‑stam en primaire sleutel. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Haalt of stelt het barcodetype in dat wordt gebruikt om deze GS1 Digital Link te coderen. Ondersteunde types zijn QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF en Code128. De standaardwaarde is QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Haalt het aantal Application Identifier-elementen op. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Haalt een kopie van alle elementen op in de oorspronkelijke volgorde. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Haalt een element op basis van zijn positie in de geordende reeks. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Haalt de Application Identifier op die wordt gebruikt als de primaire sleutel van de Digital Link. Null betekent dat de primaire sleutel automatisch wordt geselecteerd wanneer de URI wordt geconstrueerd. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Haalt het absolute URI-voorvoegsel op vóór het padsegment van de GS1 primaire sleutel. Het stamdeel bevat geen querystring of fragment. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetext te kopiëren en de enige beschikbare primaire sleutel te selecteren. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetext te kopiëren en de opgegeven primaire sleutel te gebruiken. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Parseert een niet-gecomprimeerde GS1 Digital Link URI. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Voegt een gevalideerd Application Identifier-element toe. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Haalt alle waarden voor een Application Identifier op in de oorspronkelijke volgorde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Haalt het barcodetype op dat wordt gebruikt om deze GS1 Digital Link te coderen. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Construeert de niet-gecomprimeerde GS1 Digital Link URI. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Haalt de eerste waarde voor een Application Identifier op. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Initialiseert deze instantie vanuit een niet-gecomprimeerde GS1 Digital Link URI. De bestaande toestand wordt alleen vervangen nadat de opgegeven URI succesvol is geparseerd. Het geselecteerde barcodetype wordt behouden. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Maakt een onafhankelijke GS1-codetext aan die de huidige GS1-elementen bevat. Alleen-URI-informatie wordt niet opgenomen. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Retourneert de niet-gecomprimeerde GS1 Digital Link URI. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formatteert de huidige objectstatus als een niet-gecomprimeerde GS1 Digital Link URI. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Pogt een niet-gecomprimeerde GS1 Digital Link URI te parseren en retourneert gestructureerde validatiefouten. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Valideert een niet-gecomprimeerde GS1 Digital Link URI zonder een object te construeren. |

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



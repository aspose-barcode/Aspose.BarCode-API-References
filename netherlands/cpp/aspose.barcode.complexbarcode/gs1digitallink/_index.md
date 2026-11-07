---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. Vertegenwoordigt de GS1 Digital Link-codetekst voor codering en decodering als een geordende reeks Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden. De geconstrueerde codetekst is een ongecomprimeerde GS1 Digital Link-URI. Niet‑GS1 query‑parameters en URI‑fragmenten worden genegeerd bij het parseren in C++."
type: docs
weight: 600
url: /nl/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Stelt GS1 Digital Link-codetext voor voor codering en decodering als een geordende reeks Application Identifier‑elementen. De bronvolgorde en herhaalde Application Identifiers worden behouden. De geconstrueerde codetext is een ongecomprimeerde GS1 Digital Link‑URI. Niet‑GS1 query‑parameters en URI‑fragmenten worden genegeerd bij het parseren.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Voegt een gevalideerd Application Identifier‑element toe. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetekst te kopiëren en de enige beschikbare primaire sleutel te selecteren. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Maakt een GS1 Digital Link aan door alle elementen van de GS1-codetekst te kopiëren en de opgegeven primaire sleutel te gebruiken. |
| [get_BarcodeType](./get_barcodetype/)() const | Haalt het type barcode op dat wordt gebruikt om deze GS1 Digital Link te coderen. Ondersteunde types zijn QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF en Code128. De standaardwaarde is QR. |
| [get_Count](./get_count/)() | Haalt het aantal Application Identifier‑elementen op. |
| [get_Elements](./get_elements/)() | Haalt een kopie van alle elementen op in de bronvolgorde. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Haalt de Application Identifier op die wordt gebruikt als de primaire sleutel van de Digital Link. Null betekent dat de primaire sleutel automatisch wordt geselecteerd wanneer de URI wordt geconstrueerd. |
| [get_UriStem](./get_uristem/)() const | Haalt het absolute URI‑voorvoegsel op vóór het padsegment van de GS1‑primaire sleutel. De stam bevat geen query‑string of fragment. |
| [GetAll](./getall/)(System::String) | Haalt alle waarden op voor een Application Identifier in bronvolgorde. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op dat wordt gebruikt om deze GS1 Digital Link te coderen. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert de ongecomprimeerde GS1 Digital Link-URI. |
| [GetFirst](./getfirst/)(System::String) | Haalt de eerste waarde op voor een Application Identifier. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Initialiseert een lege GS1 Digital Link met de opgegeven URI-stam. De primaire sleutel wordt automatisch geselecteerd wanneer er precies één primaire-sleutelkandidaat aanwezig is. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Initialiseert een lege GS1 Digital Link met de opgegeven URI-stam en primaire sleutel. |
| [idx_get](./idx_get/)(int32_t) | Haalt een element op op basis van zijn positie in de geordende reeks. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert deze instantie vanuit een ongecomprimeerde GS1 Digital Link-URI. De bestaande status wordt alleen vervangen nadat de opgegeven URI succesvol is geparseerd. Het geselecteerde barcode‑type wordt behouden. |
| static [Parse](./parse/)(System::String) | Parseert een ongecomprimeerde GS1 Digital Link-URI. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het barcode‑type in dat wordt gebruikt om deze GS1 Digital Link te coderen. Ondersteunde types zijn QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF en Code128. De standaardwaarde is QR. |
| [ToGS1Codetext](./togs1codetext/)() | Maakt een onafhankelijke GS1-codetekst aan die de huidige GS1‑elementen bevat. Alleen-URI‑informatie wordt niet opgenomen. |
| [ToString](./tostring/)() const override | Retourneert de ongecomprimeerde GS1 Digital Link-URI. |
| [ToUriString](./touristring/)() | Formateert de huidige objectstatus als een ongecomprimeerde GS1 Digital Link-URI. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Probeert een ongecomprimeerde GS1 Digital Link-URI te parseren en retourneert gestructureerde validatiefouten. |
| static [Validate](./validate/)(System::String) | Valideert een ongecomprimeerde GS1 Digital Link-URI zonder een object te construeren. |
## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

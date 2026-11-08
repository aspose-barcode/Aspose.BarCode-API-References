---
title: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::GS1DigitalLink class. Representerar GS1 Digital Link-kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier-element. Källordning och upprepade Application Identifier bevaras. Den konstruerade kodtexten är en okomprimerad GS1 Digital Link URI. Icke-GS1-frågeparametrar och URI-fragment ignoreras vid parsning i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class


Representerar GS1 Digital Link‑kodtext för kodning och avkodning som en ordnad sekvens av Application Identifier‑element. Källordningen och upprepade Application Identifier bevaras. Den konstruerade kodtexten är en okomprimerad GS1 Digital Link‑URI. Icke‑GS1‑frågeparametrar och URI‑fragment ignoreras vid parsning.

```cpp
class GS1DigitalLink : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Lägger till ett validerat Application Identifier-element. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1-kodtext och välja den enda tillgängliga primära nyckeln. |
| static [Create](./create/)(System::String, System::SharedPtr\<GS1Codetext\>, System::String) | Skapar en GS1 Digital Link genom att kopiera alla element från GS1-kodtext och använda den angivna primära nyckeln. |
| [get_BarcodeType](./get_barcodetype/)() const | Hämtar streckkodstypen som används för att koda denna GS1 Digital Link. Stödda typer är QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF och Code128. Standardvärdet är QR. |
| [get_Count](./get_count/)() | Hämtar antalet Application Identifier-element. |
| [get_Elements](./get_elements/)() | Hämtar en kopia av alla element i källordning. |
| [get_PrimaryApplicationIdentifier](./get_primaryapplicationidentifier/)() const | Hämtar Application Identifier som används som Digital Link:s primära nyckel. Null betyder att den primära nyckeln väljs automatiskt när URI:n konstrueras. |
| [get_UriStem](./get_uristem/)() const | Hämtar det absoluta URI-prefixet före GS1:s primära nyckelvägssegment. Stammen innehåller ingen frågesträng eller fragment. |
| [GetAll](./getall/)(System::String) | Hämtar alla värden för en Application Identifier i källordning. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstypen som används för att koda denna GS1 Digital Link. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Skapar den okomprimerade GS1 Digital Link‑URI:n. |
| [GetFirst](./getfirst/)(System::String) | Hämtar det första värdet för en Application Identifier. |
| [GS1DigitalLink](./gs1digitallink/)(System::String) | Initierar en tom GS1 Digital Link med den angivna URI‑stammen. Primärnyckeln väljs automatiskt när exakt en primärnyckelkandidat finns. |
| [GS1DigitalLink](./gs1digitallink/)(System::String, System::String) | Initierar en tom GS1 Digital Link med den angivna URI‑stammen och primärnyckel. |
| [idx_get](./idx_get/)(int32_t) | Hämtar ett element efter dess position i den ordnade sekvensen. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar detta objekt från en okomprimerad GS1 Digital Link‑URI. Befintligt tillstånd ersätts först när den angivna URI:n har parsats framgångsrikt. Den valda streckkodstypen bevaras. |
| static [Parse](./parse/)(System::String) | Parser en okomprimerad GS1 Digital Link‑URI. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstypen som används för att koda denna GS1 Digital Link. Stödda typer är QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF och Code128. Standardvärdet är QR. |
| [ToGS1Codetext](./togs1codetext/)() | Skapar en oberoende GS1‑kodtext som innehåller de aktuella GS1‑elementen. Information som endast gäller URI inkluderas inte. |
| [ToString](./tostring/)() const override | Returnerar den okomprimerade GS1 Digital Link‑URI:n. |
| [ToUriString](./touristring/)() | Formaterar det aktuella objektets tillstånd som en okomprimerad GS1 Digital Link‑URI. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1DigitalLink\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Försöker att parsa en okomprimerad GS1 Digital Link‑URI och returnerar strukturerade valideringsfel. |
| static [Validate](./validate/)(System::String) | Validerar en okomprimerad GS1 Digital Link‑URI utan att konstruera ett objekt. |
## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

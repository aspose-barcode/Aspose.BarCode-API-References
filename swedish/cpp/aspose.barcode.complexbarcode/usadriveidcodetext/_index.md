---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext klass"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext klass. Klass för kodning och avkodning av texten som är inbäddad i USA Driving License PDF417-koden i C++."
type: docs
weight: 2900
url: /sv/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Klass för kodning och avkodning av texten som är inbäddad i USA Driving [License](../../aspose.barcode/license/) PDF417-koden.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA Versionsnummer 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Detta nummer identifierar unikt den utfärdande jurisdiktionen och kan erhållas genom att kontakta ISO Issuing Authority (AAMVA). Det fullständiga 6-siffriga IIN bör kodas. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Jurisdiktionsspecifika fält |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Jurisdiktionsversionsnummer 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Obligatoriska element (fält) på kortet |
| [get_NumberOfEntries](./get_numberofentries/)() const | Nummer 00-99 för underfiler |
| [get_OptionalElements](./get_optionalelements/)() const | Valfria element (fält) på kortet |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Innehåller information om följande underfiler, typer, offset och längder. Viktigt: ange endast typ, offset och längd kommer att sättas automatiskt. |
| [GetBarcodeType](./getbarcodetype/)() override | Returnerar streckkodstyp för USA DL (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruera kodtext från USA DL-data |
| [InitFromString](./initfromstring/)(System::String) override | Initiera USA DL-objekt från kodtext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Sparar till XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA Versionsnummer 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Detta nummer identifierar unikt den utfärdande jurisdiktionen och kan erhållas genom att kontakta ISO Issuing Authority (AAMVA). Det fullständiga 6-siffriga IIN bör kodas. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Jurisdiktionsspecifika fält |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Jurisdiktionsversionsnummer 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Obligatoriska element (fält) på kortet |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Nummer 00-99 för underfiler |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Valfria element (fält) på kortet |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Innehåller information om följande underfiler, typer, offset och längder. Viktigt: ange endast typ, offset och längd kommer att sättas automatiskt. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Standardkonstruktor |
## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

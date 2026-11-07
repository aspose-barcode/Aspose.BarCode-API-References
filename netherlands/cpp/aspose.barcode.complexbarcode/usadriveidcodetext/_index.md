---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class. Klasse voor het coderen en decoderen van de tekst die is ingebed in de USA Driving License PDF417-code in C++."
type: docs
weight: 2900
url: /nl/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Klasse voor het coderen en decoderen van de tekst die is ingebed in de USA Driving [License](../../aspose.barcode/license/) PDF417-code.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA Versienummer 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Dit nummer identificeert de uitgevende jurisdictie uniek en kan worden verkregen door contact op te nemen met de ISO Issuing Authority (AAMVA). Het volledige 6-cijferige IIN moet worden gecodeerd. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Jurisdictiespecifieke velden |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Jurisdictieversienummer 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Verplichte elementen (velden) van de kaart |
| [get_NumberOfEntries](./get_numberofentries/)() const | Aantal 00-99 subbestanden |
| [get_OptionalElements](./get_optionalelements/)() const | Optionele elementen (velden) van de kaart |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Bevat informatie over de volgende subbestanden, typen, offsets en lengtes. Belangrijk: stel alleen type in, offset en lengte worden automatisch ingesteld. |
| [GetBarcodeType](./getbarcodetype/)() override | Retourneert barcode-type van USA DL (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeer codetekst vanuit USA DL-gegevens |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseer USA DL-object vanuit codetekst |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Opslaan naar XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA Versienummer 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Dit nummer identificeert de uitgevende jurisdictie uniek en kan worden verkregen door contact op te nemen met de ISO Issuing Authority (AAMVA). Het volledige 6-cijferige IIN moet worden gecodeerd. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Jurisdictiespecifieke velden |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Jurisdictieversienummer 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Verplichte elementen (velden) van de kaart |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Aantal 00-99 subbestanden |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Optionele elementen (velden) van de kaart |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Bevat informatie over de volgende subbestanden, typen, offsets en lengtes. Belangrijk: stel alleen type in, offset en lengte worden automatisch ingesteld. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Standaardconstructor |
## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

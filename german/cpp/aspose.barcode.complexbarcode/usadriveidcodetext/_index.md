---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext Klasse"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext Klasse. Klasse zum Kodieren und Dekodieren des im US-Führerschein PDF417-Code eingebetteten Textes in C++."
type: docs
weight: 2900
url: /de/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Klasse zum Kodieren und Dekodieren des im US-Führerschein [License](../../aspose.barcode/license/) PDF417-Code eingebetteten Textes.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA Versionsnummer 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Diese Nummer identifiziert eindeutig die ausstellende Jurisdiktion und kann durch Kontaktaufnahme mit der ISO-Ausstellungsbehörde (AAMVA) erhalten werden. Die vollständige 6‑stellige IIN sollte kodiert werden. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Jurisdiktionsspezifische Felder |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Jurisdiktionsversionsnummer 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Obligatorische Elemente (Felder) der Karte |
| [get_NumberOfEntries](./get_numberofentries/)() const | Anzahl 00-99 der Unterdateien |
| [get_OptionalElements](./get_optionalelements/)() const | Optionale Elemente (Felder) der Karte |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur Typ setzen, Offset und Länge werden automatisch gesetzt. |
| [GetBarcodeType](./getbarcodetype/)() override | Gibt den Barcode-Typ von USA DL (Pdf417) zurück |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstelle Codetext aus USA DL-Daten |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiere USA DL-Objekt aus Codetext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Speichert in XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA Versionsnummer 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Diese Nummer identifiziert eindeutig die ausstellende Jurisdiktion und kann durch Kontaktaufnahme mit der ISO-Ausstellungsbehörde (AAMVA) erhalten werden. Die vollständige 6‑stellige IIN sollte kodiert werden. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Jurisdiktionsspezifische Felder |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Jurisdiktionsversionsnummer 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Obligatorische Elemente (Felder) der Karte |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Anzahl 00-99 der Unterdateien |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Optionale Elemente (Felder) der Karte |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Enthält Informationen über die folgenden Unterdateien, Typen, Offsets und Längen. Wichtig: Nur Typ setzen, Offset und Länge werden automatisch gesetzt. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Standardkonstruktor |
## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

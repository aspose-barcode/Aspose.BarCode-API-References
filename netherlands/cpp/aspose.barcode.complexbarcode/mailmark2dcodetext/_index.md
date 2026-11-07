---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext klasse"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de Royal Mail 2D Mailmark-code in C++."
type: docs
weight: 1400
url: /nl/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Klasse voor het coderen en decoderen van de in de Royal Mail 2D Mailmark-code ingebedde tekst.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Class](./get_class/)() const | Identificeert de klasse van het item. |
| [get_CustomerContent](./get_customercontent/)() const | Optionele ruimte voor gebruik door de klant. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Coderingsmodus van Datamatrix-barcode. Standaardwaarde: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Bevat de postcode van het bezorg-[Address](../address/) met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens: Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. |
| [get_ItemID](./get_itemid/)() const | Identificeert het unieke item binnen de Supply Chain-ID. Elke Mailmark-barcode moet een ID dragen zodat het gedurende minimaal 90 dagen uniek kan worden geïdentificeerd. Maximale waarde: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Bevat de Return to Sender-postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| [get_RTSFlag](./get_rtsflag/)() const | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identificeert de unieke groep klanten die bij de mailing betrokken zijn. Maximale waarde: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identificeert de UPU-land-ID. Maximale lengte: 4 tekens. |
| [get_VersionID](./get_versionid/)() const | Identificeert de barcodeversie die relevant is voor elke Information Type-ID. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeer codetekst vanuit Mailmark-gegevens. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Constructor. Maak een standaardexemplaar van de [Mailmark2DCodetext](./) klasse. |
| [set_Class](./set_class/)(System::String) | Identificeert de klasse van het item. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Optionele ruimte voor gebruik door de klant. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Coderingsmodus van Datamatrix-barcode. Standaardwaarde: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark-type definieert de grootte van de Data Matrix-barcode. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Bevat de postcode van het bezorg-[Address](../address/) met DPS. Als het binnenland betreft, bevat de postcode/DP het volgende aantal tekens: Gebied (1 of 2 tekens) District (1 of 2 tekens) Sector (1 teken) Eenheid (2 tekens) DPS (2 tekens). De postcode en DPS moeten voldoen aan een geldig PAF®-formaat. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identificeert de Royal Mail Mailmark-barcodepayload voor elk producttype. |
| [set_ItemID](./set_itemid/)(int32_t) | Identificeert het unieke item binnen de Supply Chain-ID. Elke Mailmark-barcode moet een ID dragen zodat het gedurende minimaal 90 dagen uniek kan worden geïdentificeerd. Maximale waarde: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Bevat de Return to Sender-postcode maar geen DPS. De PC (zonder DPS) moet voldoen aan een PAF®-formaat. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Vlag die aangeeft welk niveau van Return to Sender-service wordt aangevraagd. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identificeert de unieke groep klanten die bij de mailing betrokken zijn. Maximale waarde: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identificeert de UPU-land-ID. Maximale lengte: 4 tekens. |
| [set_VersionID](./set_versionid/)(System::String) | Identificeert de barcodeversie die relevant is voor elke Information Type-ID. |
## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

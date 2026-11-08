---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext klass"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext klass. Klass för kodning och avkodning av text som är inbäddad i Royal Mail 2D Mailmark-koden i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Klass för kodning och avkodning av texten som är inbäddad i Royal Mail 2D Mailmark-koden.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Class](./get_class/)() const | Identifierar objektets klass. |
| [get_CustomerContent](./get_customercontent/)() const | Valfritt utrymme för kundens bruk. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Innehåller postnumret för leverans-[Address](../address/) med DPS. Om inlandet innehåller postnumret/DP följande antal tecken: Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®-format. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identifierar Royal Mail Mailmark-streckkodens nyttolast för varje produkttyp. |
| [get_ItemID](./get_itemid/)() const | Identifierar det unika objektet inom Supply Chain-ID. Varje Mailmark-streckkod måste bära ett ID så att det kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Innehåller Return to Sender-postkoden men ingen DPS. PC (utan DPS) måste följa ett PAF®-format. |
| [get_RTSFlag](./get_rtsflag/)() const | Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
| [get_VersionID](./get_versionid/)() const | Identifierar streckkodsversionen som relevant för varje Information Type-ID. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Skapa kodtext från Mailmark-data. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar Mailmark-data från konstruerad kodtext. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Konstruktor. Skapa standardinstans av klassen [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | Identifierar objektets klass. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Valfritt utrymme för kundens bruk. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Kodningsläge för Datamatrix-streckkod. Standardvärde: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark-typ definierar storleken på Data Matrix-streckkoden. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Innehåller postnumret för leverans-[Address](../address/) med DPS. Om inlandet innehåller postnumret/DP följande antal tecken: Område (1 eller 2 tecken) Distrikt (1 eller 2 tecken) Sektor (1 tecken) Enhet (2 tecken) DPS (2 tecken). Postnumret och DPS måste följa ett giltigt PAF®-format. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identifierar Royal Mail Mailmark-streckkodens nyttolast för varje produkttyp. |
| [set_ItemID](./set_itemid/)(int32_t) | Identifierar det unika objektet inom Supply Chain-ID. Varje Mailmark-streckkod måste bära ett ID så att det kan identifieras unikt i minst 90 dagar. Maxvärde: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Innehåller Return to Sender-postkoden men ingen DPS. PC (utan DPS) måste följa ett PAF®-format. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Flagga som indikerar vilken nivå av Return to Sender-tjänst som begärs. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identifierar den unika gruppen av kunder som är involverade i utskicket. Maxvärde: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identifierar UPU-land-ID. Maxlängd: 4 tecken. |
| [set_VersionID](./set_versionid/)(System::String) | Identifierar streckkodsversionen som relevant för varje Information Type-ID. |
## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

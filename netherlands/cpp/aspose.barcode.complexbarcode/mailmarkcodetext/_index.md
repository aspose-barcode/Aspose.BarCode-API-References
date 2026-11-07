---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. Klasse voor het coderen en decoderen van de tekst die is ingebed in de 4‑state Royal Mailmark-code in C++."
type: docs
weight: 1500
url: /nl/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Klasse voor het coderen en decoderen van de in de 4‑state Royal Mailmark-code ingebedde tekst.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Class](./get_class/)() const | \"0\" - Null of Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) \"5\" - Uitgesteld (Retail) \"6\" - Lucht (Retail) (voor mogelijk toekomstig gebruik) \"7\" - Oppervlak (Retail) (voor mogelijk toekomstig gebruik) \"8\" - Premium (Network Access) \"9\" - Standaard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | De PC en DP moeten voldoen aan een PAF-formaat. Een tekenreeks van negen tekens die een internationale \"XY11     \" aangeeft (let op de 5 achterliggende spaties) of een patroon van tekens dat een binnenlandse sorteercode aangeeft. Een binnenlandse sorteercode bestaat uit een outward postcode, een inward postcode, en een Delivery Point Suffix. |
| [get_Format](./get_format/)() const | \"0\" – Null of Test \"1\" – Letter \"2\" – Grote Letter |
| [get_ItemID](./get_itemid/)() const | Maximumwaarde is 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [get_VersionID](./get_versionid/)() const | Momenteel \"1\" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeer codetekst vanuit Mailmark-gegevens. |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert Mailmark-gegevens vanuit geconstrueerde codetekst. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Initialiseert een nieuw exemplaar van de [MailmarkCodetext](./) klasse. |
| [set_Class](./set_class/)(System::String) | \"0\" - Null of Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (voor mogelijk toekomstig gebruik) \"5\" - Uitgesteld (Retail) \"6\" - Lucht (Retail) (voor mogelijk toekomstig gebruik) \"7\" - Oppervlak (Retail) (voor mogelijk toekomstig gebruik) \"8\" - Premium (Network Access) \"9\" - Standaard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | De PC en DP moeten voldoen aan een PAF-formaat. Een tekenreeks van negen tekens die een internationale \"XY11     \" aangeeft (let op de 5 achterliggende spaties) of een patroon van tekens dat een binnenlandse sorteercode aangeeft. Een binnenlandse sorteercode bestaat uit een outward postcode, een inward postcode, en een Delivery Point Suffix. |
| [set_Format](./set_format/)(int32_t) | \"0\" – Null of Test \"1\" – Letter \"2\" – Grote Letter |
| [set_ItemID](./set_itemid/)(int32_t) | Maximumwaarde is 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Maximumwaarden zijn 99 voor Barcode C en 999999 voor Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | Momenteel \"1\" – Voor Mailmark-barcode (0 en 2 tot 9 en A tot Z gereserveerd voor toekomstig gebruik) |
## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

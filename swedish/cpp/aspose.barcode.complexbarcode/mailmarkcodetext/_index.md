---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext klass"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext klass. Klass för kodning och avkodning av text som är inbäddad i den fyrastegs Royal Mailmark-koden i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Klass för kodning och avkodning av texten som är inbäddad i den fyrtillstånds Royal Mailmark-koden.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiell framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiell framtida användning) "7" - Yta (Retail) (för potentiell framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC och DP måste följa ett PAF-format. Nio tecken lång sträng som anger internationell "XY11     " (observera de 5 efterföljande mellanslagen) eller ett teckenmönster som anger en inhemsk sorteringskod. En inhemsk sorteringskod består av ett utåtriktat postnummer, ett inåtriktat postnummer och ett leveranspunktsuffix. |
| [get_Format](./get_format/)() const | "0" – Null eller Test "1" – Brev "2" – Stort brev |
| [get_ItemID](./get_itemid/)() const | Maximalt värde är 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [get_VersionID](./get_versionid/)() const | För närvarande "1" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Skapa kodtext från Mailmark-data. |
| [InitFromString](./initfromstring/)(System::String) override | Initierar Mailmark-data från konstruerad kodtext. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Initierar en ny instans av klassen [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - Null eller Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (för potentiell framtida användning) "5" - Uppskjuten (Retail) "6" - Luft (Retail) (för potentiell framtida användning) "7" - Yta (Retail) (för potentiell framtida användning) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC och DP måste följa ett PAF-format. Nio tecken lång sträng som anger internationell "XY11     " (observera de 5 efterföljande mellanslagen) eller ett teckenmönster som anger en inhemsk sorteringskod. En inhemsk sorteringskod består av ett utåtriktat postnummer, ett inåtriktat postnummer och ett leveranspunktsuffix. |
| [set_Format](./set_format/)(int32_t) | "0" – Null eller Test "1" – Brev "2" – Stort brev |
| [set_ItemID](./set_itemid/)(int32_t) | Maximalt värde är 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Maximala värden är 99 för Barcode C och 999999 för Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | För närvarande "1" – För Mailmark-streckkod (0 och 2 till 9 samt A till Z reserverade för framtida användning) |
## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

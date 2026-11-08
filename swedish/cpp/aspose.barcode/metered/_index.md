---
title: "Aspose::BarCode::Metered klass"
linktitle: "Mätad"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Metered klass. Tillhandahåller metoder för att ställa in mätad nyckel i C++."
type: docs
weight: 500
url: /sv/cpp/aspose.barcode/metered/
---
## Metered class


Tillhandahåller metoder för att ställa in mätad nyckel.

```cpp
class Metered : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Hämtar konsumtionskredit |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Hämtar konsumtionsfilens storlek |
| [GetProductName](./getproductname/)() | Hämtar namn på licensierad produkt |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Kontrollera om mätad är licensierad |
| [Metered](./metered/)() | Initierar en ny instans av denna klass. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Sätter mätad publik och privat nyckel. Om du köper en mätad licens, när du startar applikationen, bör detta API anropas, normalt räcker detta. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus; för att undvika ett sådant fall bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |
## Anmärkningar


I det här exemplet kommer ett försök att göras att sätta mätad publik och privat nyckel

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> komponentens jar-fil:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Se även

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)

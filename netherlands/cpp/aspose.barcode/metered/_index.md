---
title: "Aspose::BarCode::Metered klasse"
linktitle: "Metered"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Metered klasse. Biedt methoden om de metered‑sleutel in C++ in te stellen."
type: docs
weight: 500
url: /nl/cpp/aspose.barcode/metered/
---
## Metered class


Biedt methoden om de meter‑sleutel in te stellen.

```cpp
class Metered : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Haalt verbruikskrediet op |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Haalt verbruikbestandsgrootte op |
| [GetProductName](./getproductname/)() | Haalt naam van gelicentieerd product op |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Controleer of metered is gelicentieerd |
| [Metered](./metered/)() | Initialiseert een nieuw exemplaar van deze klasse. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Stelt de metered openbare en privé‑sleutel in. Als u een metered‑licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. Echter, als het altijd mislukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie op evaluatiestatus gezet. Om zo’n geval te voorkomen, dient u regelmatig de licentiestatus te controleren; is deze op evaluatiestatus, roep dan deze API opnieuw aan. |
## Opmerkingen


In dit voorbeeld wordt geprobeerd de metered openbare en privé‑sleutel in te stellen.

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

<java> het component‑jar‑bestand:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Zie ook

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)

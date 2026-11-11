---
title: "Klasse Metered"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Metered klasse. Biedt methoden om de metered‑sleutel in te stellen"
type: docs
weight: 1770
url: /nl/net/aspose.barcode/metered/
---
## Metered class

Biedt methoden om een meter‑sleutel in te stellen.

```csharp
public class Metered
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Haalt de naam van het gelicentieerde product op |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Stelt de openbare en private metered‑sleutel in. Als u een metered‑licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. Als het echter steeds mislukt om consumptiegegevens te uploaden en de 24‑uurgrens wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Haalt consumptie‑credit op |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Haalt de bestandsgrootte van het verbruik op |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Controleer of meterstand gelicentieerd is |

## Voorbeelden

In dit voorbeeld wordt geprobeerd de gemeten openbare en privésleutel in te stellen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Zie ook

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)



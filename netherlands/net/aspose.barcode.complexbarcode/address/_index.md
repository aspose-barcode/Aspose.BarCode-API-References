---
title: "Klasse Address"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.Address klasse. Adres van schuldeiser of schuldenaar."
type: docs
weight: 480
url: /nl/net/aspose.barcode.complexbarcode/address/
---
## Address class

Adres van crediteur of debiteur.

U kunt ofwel straat, huisnummer, postcode en plaats (type gestructureerd adres) of adresregel 1 en 2 (type gecombineerde adresselementen) instellen. Het type wordt automatisch ingesteld zodra een van deze velden is ingevuld. Voor het instellen van de velden is het adrestype onbepaald. Als velden van beide types worden ingesteld, ontstaat een conflicterend adrestype. Naam en landcode moeten altijd worden ingesteld, tenzij alle velden leeg zijn.

```csharp
public sealed class Address : IEquatable<Address>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Address](address/)() | Maakt een instantie van Address aan |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Haalt op of stelt adresregel 1 in. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Haalt op of stelt adresregel 2 in. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Haalt op of stelt de tweeletterige ISO-landcode in. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Haalt op of stelt het huisnummer in. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Haalt op of stelt de naam in, ofwel de voor- en achternaam van een natuurlijke persoon of de bedrijfsnaam van een rechtspersoon. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Haalt op of stelt de postcode in. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Haalt op of stelt de straat in. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Haalt op of stelt de plaats of stad in. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Haalt het adrestype op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Leegt alle velden en stelt het type in op Onbepaald. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Bepaalt of het opgegeven adres gelijk is aan het huidige adres. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Haalt de hashcode op voor deze instantie. |

### Zie ook

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



---
title: Address
second_title: Aspose.BarCode för .NET API-referens
description: Adress till borgenären eller gäldenären.
type: docs
weight: 300
url: /sv/net/aspose.barcode.complexbarcode/address/
---
## Address class

Adress till borgenären eller gäldenären.

Du kan antingen ställa in gata, husnummer, postnummer och stad (typstrukturerad adress ) eller adressrad 1 och 2 (typkombinerade adresselement ). Typen är automatiskt set när något av dessa fält är inställt. Innan du ställer in fälten är adresstypenobestämd . Om fält av båda typerna är inställda blir adresstypenmotstridig . Namn och landskod måste alltid anges om inte alla fält är tomma.

```csharp
public sealed class Address : IEquatable<Address>
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Address](address)() | Skapar instans av Address |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1) { get; set; } | Hämtar eller ställer in adressraden 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2) { get; set; } | Hämtar eller ställer in adressraden 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode) { get; set; } | Hämtar eller ställer in ISO-landskoden på två bokstäver. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno) { get; set; } | Hämtar eller ställer in husnumret. |
| [Name](../../aspose.barcode.complexbarcode/address/name) { get; set; } | Hämtar eller anger namnet, antingen för- och efternamnet på en fysisk person eller företagsnamnet på en juridisk person. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode) { get; set; } | Hämtar eller ställer in postnumret. |
| [Street](../../aspose.barcode.complexbarcode/address/street) { get; set; } | Får eller sätter gatan. |
| [Town](../../aspose.barcode.complexbarcode/address/town) { get; set; } | Hämtar eller ställer in staden eller staden. |
| [Type](../../aspose.barcode.complexbarcode/address/type) { get; } | Hämtar adresstypen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear)() | Rensar alla fält och ställer in typen tillUndetermined . |
| [Equals](../../aspose.barcode.complexbarcode/address/equals#equals)(Address) | Bestämmer om den angivna adressen är lika med den aktuella adressen. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals#equals_1)(object) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode)() | Hämtar hashkoden för den här instansen. |

### Se även

* namnutrymme [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* hopsättning [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
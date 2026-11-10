---
title: "Klasse Address"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.Address Klasse. Adresse des Gläubigers oder Schuldners."
type: docs
weight: 480
url: /de/net/aspose.barcode.complexbarcode/address/
---
## Address class

Adresse des Gläubigers oder Schuldners.

Sie können entweder Straße, Hausnummer, Postleitzahl und Ort (Typ strukturierte Adresse) oder Adresszeile 1 und 2 (Typ kombinierte Adresselemente) festlegen. Der Typ wird automatisch gesetzt, sobald eines dieser Felder gesetzt ist. Vor dem Setzen der Felder ist der Adresstyp unbestimmt. Wenn Felder beider Typen gesetzt werden, wird der Adresstyp konfliktär. Name und Ländercode müssen immer gesetzt sein, es sei denn, alle Felder sind leer.

```csharp
public sealed class Address : IEquatable<Address>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Address](address/)() | Erstellt eine Instanz von Address |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Liest oder setzt die Adresszeile 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Liest oder setzt die Adresszeile 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Liest oder setzt den zweibuchstabigen ISO-Ländercode. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Liest oder setzt die Hausnummer. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Liest oder setzt den Namen, entweder Vor‑ und Nachname einer natürlichen Person oder den Firmennamen einer juristischen Person. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Liest oder setzt die Postleitzahl. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Liest oder setzt die Straße. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Liest oder setzt die Stadt oder den Ort. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Liest den Adresstyp. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Löscht alle Felder und setzt den Typ auf Unbestimmt. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Bestimmt, ob die angegebene Adresse der aktuellen Adresse entspricht. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt entspricht. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Liefert den Hashcode für diese Instanz. |

### Siehe auch

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



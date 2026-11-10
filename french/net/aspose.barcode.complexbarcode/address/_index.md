---
title: "Classe Address"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.ComplexBarcode.Address classe. Adresse du créancier ou du débiteur"
type: docs
weight: 480
url: /fr/net/aspose.barcode.complexbarcode/address/
---
## Address class

Adresse du créancier ou du débiteur.

Vous pouvez soit définir la rue, le numéro de maison, le code postal et la ville (type adresse structurée) ou la ligne d'adresse 1 et 2 (type éléments d'adresse combinés). Le type est automatiquement défini dès qu'un de ces champs est renseigné. Avant de définir les champs, le type d'adresse est indéterminé. Si les champs des deux types sont définis, le type d'adresse devient conflictuel. Le nom et le code pays doivent toujours être définis sauf si tous les champs sont vides.

```csharp
public sealed class Address : IEquatable<Address>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Address](address/)() | Crée une instance de Address |

## Propriétés

| Nom | Description |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Obtient ou définit la ligne d'adresse 1. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Obtient ou définit la ligne d'adresse 2. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | Obtient ou définit le code pays ISO à deux lettres. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Obtient ou définit le numéro de maison. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | Obtient ou définit le nom, soit le prénom et le nom de famille d'une personne physique, soit le nom de l'entreprise d'une personne morale. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Obtient ou définit le code postal. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Obtient ou définit la rue. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Obtient ou définit la ville ou la cité. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Obtient le type d'adresse. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Efface tous les champs et définit le type sur Indéterminé. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Détermine si l'adresse spécifiée est égale à l'adresse actuelle. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Détermine si l'objet spécifié est égal à l'objet actuel. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Obtient le code de hachage pour cette instance. |

### Voir aussi

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



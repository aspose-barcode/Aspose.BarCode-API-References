---
title: "Classe SecondaryAndAdditionalData"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.SecondaryAndAdditionalData. Classe pour stocker les données secondaires et supplémentaires du HIBC LIC"
type: docs
weight: 770
url: /fr/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

Classe pour le stockage des données secondaires et supplémentaires HIBC LIC.

```csharp
public class SecondaryAndAdditionalData
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | Identifie la date de fabrication. La date de fabrication peut être définie sur DateTime.MinValue afin de ne pas utiliser ce champ. Valeur par défaut : DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | Identifie la date d'expiration. Sera utilisé si ExpiryDateFormat n'est pas défini sur None. |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | Identifie le format de la date d'expiration. |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | Identifie le numéro de lot ou de lot. Lot/batch number doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles. |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | Identifie la quantité, doit être une valeur entière de 0 à 500. La quantité peut être définie à -1 afin de ne pas utiliser ce champ. Valeur par défaut : -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | Identifie le numéro de série. Serial number doit être une chaîne alphanumérique d'une longueur maximale de 18 symboles. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `SecondaryAndAdditionalData` spécifiée. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | Instancie les données supplémentaires secondaires et additionnelles à partir du format chaîne selon la spécification HIBC LIC. |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | Convertit les données au format chaîne selon la spécification HIBC LIC. |

### Voir aussi

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



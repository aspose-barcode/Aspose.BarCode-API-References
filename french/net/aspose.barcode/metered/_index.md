---
title: "Classe Metered"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Metered. Fournit des méthodes pour définir la clé métérée"
type: docs
weight: 1770
url: /fr/net/aspose.barcode/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Obtient le nom du produit sous licence |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Définit la clé publique et privée métérée. Si vous achetez une licence métérée, au démarrage de l'application, cette API doit être appelée ; normalement, cela suffit. Cependant, si le téléchargement des données de consommation échoue constamment et dépasse 24 heures, la licence sera mise en statut d'évaluation. Pour éviter ce cas, vous devez vérifier régulièrement le statut de la licence ; si elle est en statut d'évaluation, appelez à nouveau cette API. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Obtient la taille du fichier de consommation |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Vérifiez si la facturation à l'usage est licenciée |

## Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée de la facturation à l'usage

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Voir aussi

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)



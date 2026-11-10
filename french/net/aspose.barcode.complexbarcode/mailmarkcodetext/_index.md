---
title: "Classe MailmarkCodetext"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.ComplexBarcode.MailmarkCodetext. Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états."
type: docs
weight: 670
url: /fr/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Nul ou Test "1" - 1C (Vente au détail) "2" - 2C (Vente au détail) "3" - 3C (Vente au détail) "4" - Premium (RetailPublishing Mail) (pour une utilisation future éventuelle) "5" - Différé (Vente au détail) "6" - Air (Vente au détail) (pour une utilisation future éventuelle) "7" - Surface (Vente au détail) (pour une utilisation future éventuelle) "8" - Premium (Accès Réseau) "9" - Standard (Accès Réseau) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | Le PC et le DP doivent être conformes à un format PAF. Chaîne de neuf caractères désignant l'international "XY11 " (notez les 5 espaces de fin) ou un motif de caractères désignant un code de tri domestique. Un code de tri domestique se compose d'un code postal sortant, d'un code postal entrant et d'un suffixe de point de livraison. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Nul ou Test "1" – Lettre "2" – Grande Lettre |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | La valeur maximale est 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Les valeurs maximales sont 99 pour le code-barres C et 999999 pour le code-barres L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Actuellement "1" – Pour le code-barres Mailmark (0 et 2 à 9 et A à Z réservés pour une utilisation future) |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Obtient le type de code-barres. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Construire le texte de code à partir des données Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Initialise les données Mailmark à partir du texte de code construit. |

### Voir aussi

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



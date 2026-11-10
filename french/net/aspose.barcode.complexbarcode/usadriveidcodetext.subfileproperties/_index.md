---
title: "Classe USADriveIdCodetext.SubfileProperties"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties classe. Les propriétés du sous-fichier USA DL, le décalage et la longueur sont définis automatiquement"
type: docs
weight: 840
url: /fr/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

Les propriétés du sous-fichier USA DL, le décalage et la longueur sont définis automatiquement.

```csharp
public class SubfileProperties
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du Subfile en octets. Le terminateur de segment doit être inclus dans le calcul de la longueur du sous-fichier. Un terminateur de segment = 1. Chaque sous-fichier doit commencer par le type de Subfile à deux caractères et ces deux caractères doivent également être inclus dans la longueur. |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | Valeur numérique à 4 chiffres qui spécifie le nombre d'octets depuis le début du fichier jusqu'à l'emplacement des données liées au sous-fichier particulier. Le premier octet du fichier se trouve à l'offset 0. |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | Type de sous-fichier de 2 octets, comme "DL" |

### Voir aussi

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



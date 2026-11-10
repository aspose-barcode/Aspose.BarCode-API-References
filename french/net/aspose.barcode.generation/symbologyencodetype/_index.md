---
title: "Classe SymbologyEncodeType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.SymbologyEncodeType classe. Type d'encodage de symbologie. Voir EncodeTypes pour obtenir une instance."
type: docs
weight: 1710
url: /fr/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Type d'encodage de la symbologie. Voir EncodeTypes pour obtenir une instance.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Obtient une classification de cette symbologie. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Obtient un index du type d'encodage. |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Obtient un nom du type d'encodage. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur [`BaseEncodeType`](../baseencodetype/) spécifiée. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur [`BaseEncodeType`](../baseencodetype/) spécifiée. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Convertit l'instance de BaseEncodeType en sa représentation chaîne équivalente. Le format de la chaîne est : "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Renvoie le nom du BaseEncodeType donné sous forme de chaîne. |

## Exemples

Cet exemple montre comment obtenir une instance de la classe SymbologyEncodeType.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### Voir aussi

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Classe MultiDecodeType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.MultiDecodeType. Type de décodage composite."
type: docs
weight: 320
url: /fr/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Type de décodage Composite.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Initialise une nouvelle instance de la classe `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Initialise une nouvelle instance de la classe `MultiDecodeType`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Renvoie un nombre de types simples. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Ajoute un autre [`SingleDecodeType`](../singledecodetype/) au MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Vérifie si cela contient tous les types des types de code-barres. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Contient un des types |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur `MultiDecodeType` spécifiée. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `MultiDecodeType` spécifiée. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Renvoie une valeur indiquant si cette collection de types de décodage ne contient que la valeur [`SingleDecodeType`](../singledecodetype/) spécifiée. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Exclut [`SingleDecodeType`](../singledecodetype/) du MultiDecodeType et renvoie une nouvelle instance de MultiDecodeType. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Représente une liste de types simples. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Méthode remplacée représentant le MultiDecodeType sous forme de chaîne. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |

## Exemples

Cet exemple montre comment créer des types MultiDecode composés qui combinent SingleDecodeType et les types MultiDecode.

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### Voir aussi

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



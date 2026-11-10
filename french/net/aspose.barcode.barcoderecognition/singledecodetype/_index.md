---
title: "Classe SingleDecodeType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType classe. Type de décodage unique. Voir le type de décodage pour obtenir une instance"
type: docs
weight: 390
url: /fr/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Type de décodage unique. Voir le type de décodage pour obtenir une instance.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Obtient un indice du type de décodage |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Obtient le nom du type de décodage |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Convertit la représentation sous forme de chaîne du nom d'un SingleDecodeType en son instance. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Renvoie une valeur indiquant si cette instance est incluse dans la liste spécifiée. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de [`BaseDecodeType`](../basedecodetype/). |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Renvoie une valeur indiquant si la collection spécifiée de [`MultiDecodeType`](../multidecodetype/) ne contient que ce type de décodage. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de `SingleDecodeType`. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de `SingleDecodeType`. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Convertit l'instance de SingleDecodeType en sa représentation sous forme de chaîne équivalente. Le format de la chaîne est : "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Renvoie le nom du SingleDecodeType donné sous forme de chaîne. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Convertit l'instance de SingleDecodeType en sa représentation sous forme de chaîne équivalente. Le format de la chaîne est : "Index:-1; Name:None". |

## Exemples

Cet exemple montre comment obtenir une instance d'un type de décodage unique.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Voir aussi

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: "Classe BaseDecodeType"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.BarCodeRecognition.BaseDecodeType. Classe de base pour MultiDecodeType et SingleDecodeType"
type: docs
weight: 130
url: /fr/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Classe de base pour MultiDecodeType et SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Détermine si l'un des types de décodage fournis est inclus dans |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur `BaseDecodeType` spécifiée. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur [`MultiDecodeType`](../multidecodetype/) spécifiée. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Renvoie une valeur indiquant si cette instance est égale à une valeur `BaseDecodeType` spécifiée. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Renvoie une valeur indiquant si cette instance est égale à une valeur [`SingleDecodeType`](../singledecodetype/) spécifiée. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Renvoie le code de hachage pour cette instance. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Convertit la représentation sous forme de chaîne d'un BaseDecodeType en son instance, après avoir déterminé le type concret. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | Convertit la représentation sous forme de chaîne d'un MultiDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Convertit la représentation sous forme de chaîne d'un SingleDecodeType en son instance. Une valeur de retour indique si la conversion a réussi ou échoué. |

## Exemples

Cet exemple montre comment utiliser BaseDecodeType avec SingleDecodeType et MultiDecodeType

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Voir aussi

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



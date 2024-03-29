---
title: SingleDecodeType
second_title: Aspose.BarCode voor .NET API-referentie
description: Enkel decodeertype. Zie type decoderen om instantie te krijgen.
type: docs
weight: 290
url: /nl/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Enkel decodeertype. Zie type decoderen om instantie te krijgen.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Krijgt een index van decodeertype |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Krijgt een naam van decodeertype |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Converteert de tekenreeksrepresentatie van de naam van een SingleDecodeType naar zijn instantie. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Retourneert een waarde die aangeeft of deze instantie is opgenomen in de opgegeven lijst. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven[`BaseDecodeType`](../basedecodetype/) waarde. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(MultyDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven[`MultyDecodeType`](../multydecodetype/) waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven`SingleDecodeType` waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven`SingleDecodeType` waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Retourneert de hash-code voor deze instantie. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Converteert de instantie van SingleDecodeType naar zijn equivalente tekenreeksrepresentatie. De tekenreeksindeling is: "Index:-1; Naam:Geen". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Retourneert de naam van het gegeven SingleDecodeType als een string. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Converteert de instantie van SingleDecodeType naar zijn equivalente tekenreeksrepresentatie. De tekenreeksindeling is: "Index:-1; Naam:Geen". |

### Voorbeelden

Dit voorbeeld laat zien hoe u een exemplaar van een enkel decodeertype kunt krijgen.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Zie ook

* class [BaseDecodeType](../basedecodetype/)
* naamruimte [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

---
title: "Klasse MultiDecodeType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType klasse. Samengestelde decodeertype"
type: docs
weight: 320
url: /nl/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Composite decodeertype.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Initialiseert een nieuwe instantie van de `MultiDecodeType`‑klasse. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Initialiseert een nieuwe instantie van de `MultiDecodeType`‑klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Retourneert een aantal enkelvoudige types. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Voegt nog één [`SingleDecodeType`](../singledecodetype/) toe aan de MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Controleer of dit alle types van barcodetypes bevat. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Bevat een van de types |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`BaseDecodeType`](../basedecodetype/)-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `MultiDecodeType`-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `MultiDecodeType`-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Retourneert een waarde die aangeeft of deze collectie decodeertypes alleen de opgegeven [`SingleDecodeType`](../singledecodetype/)-waarde bevat. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Sluit [`SingleDecodeType`](../singledecodetype/) uit van de MultiDecodeType en retourneert een nieuwe MultiDecodeType‑instantie. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Stelt een lijst van enkelvoudige types voor. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Overschreven methode die MultiDecodeType als een string weergeeft. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |

## Voorbeelden

Dit voorbeeld toont hoe samengestelde MultiDecode-types te maken die SingleDecodeType en MultiDecode-types combineren.

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

### Zie ook

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



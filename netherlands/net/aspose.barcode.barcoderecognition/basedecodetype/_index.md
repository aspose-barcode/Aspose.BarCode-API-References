---
title: "Klasse BaseDecodeType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType klasse. Basisklasse voor MultiDecodeType en SingleDecodeType"
type: docs
weight: 130
url: /nl/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Basisklasse voor MultiDecodeType en SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Bepaalt of een van de opgegeven decodeertypen is opgenomen in |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `BaseDecodeType`-waarde. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`MultiDecodeType`](../multidecodetype/)-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `BaseDecodeType`-waarde. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`SingleDecodeType`](../singledecodetype/)-waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Converteert de tekenreeksrepresentatie van een BaseDecodeType naar de bijbehorende instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | Converteert de tekenreeksrepresentatie van een MultiDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Converteert de tekenreeksrepresentatie van een SingleDecodeType naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |

## Voorbeelden

Dit voorbeeld toont hoe BaseDecodeType te gebruiken met SingleDecodeType en MultiDecodeType

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### Zie ook

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



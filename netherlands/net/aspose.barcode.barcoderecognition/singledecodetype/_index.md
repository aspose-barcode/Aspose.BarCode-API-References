---
title: "Klasse SingleDecodeType"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType klasse. Enkele decodeertype. Zie decodeertype om een instantie te krijgen."
type: docs
weight: 390
url: /nl/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Enkel decodeertype. Zie decodeertype om een instantie te krijgen.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Haalt een index op van het decodeertype. |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Haalt een naam op van het decodeertype. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Converteert de tekenreeksrepresentatie van de naam van een SingleDecodeType naar de bijbehorende instantie. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Retourneert een waarde die aangeeft of deze instantie is opgenomen in de opgegeven lijst. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [`BaseDecodeType`](../basedecodetype/)-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Retourneert een waarde die aangeeft of de opgegeven [`MultiDecodeType`](../multidecodetype/)-collectie alleen dit decodeertype bevat. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `SingleDecodeType`-waarde. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `SingleDecodeType`-waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Converteert de instantie van SingleDecodeType naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Retourneert de naam van de opgegeven SingleDecodeType als een tekenreeks. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Converteert de instantie van SingleDecodeType naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None". |

## Voorbeelden

Dit voorbeeld toont hoe een instantie van een enkel decodeertype op te halen.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### Zie ook

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



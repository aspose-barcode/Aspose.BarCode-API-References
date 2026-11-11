---
title: "Klass MultiDecodeType"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType-klass. Sammansatt avkodningstyp"
type: docs
weight: 320
url: /sv/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Sammansatt avkodningstyp.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Initierar en ny instans av klassen `MultiDecodeType`. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Initierar en ny instans av klassen `MultiDecodeType`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Returnerar ett antal enkla typer. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Lägger till en till [`SingleDecodeType`](../singledecodetype/) till MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Kontrollera om detta innehåller alla typer från streckkodstyper. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Innehåller någon av typerna |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [`BaseDecodeType`](../basedecodetype/)-värde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat `MultiDecodeType`-värde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat `MultiDecodeType`-värde. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Returnerar ett värde som indikerar om denna samling av avkodningstyper endast innehåller det specificerade [`SingleDecodeType`](../singledecodetype/)-värdet. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Exkluderar [`SingleDecodeType`](../singledecodetype/) från MultiDecodeType och returnerar en ny MultiDecodeType-instans. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Representerar en lista med enkla typer. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Åsidosatt metod som representerar MultiDecodeType som en sträng. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Konverterar strängrepresentationen av en MultiDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |

## Exempel

Detta exempel visar hur man skapar sammansatta MultiDecode-typer som kombinerar SingleDecodeType och MultiDecode-typer.

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

### Se även

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



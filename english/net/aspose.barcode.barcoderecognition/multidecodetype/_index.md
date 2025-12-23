---
title: Class MultiDecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.MultiDecodeType class. Composite decode type
type: docs
weight: 290
url: /net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

Composite decode type.

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## Constructors

| Name | Description |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | Initializes a new instance of the `MultiDecodeType` class. |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | Initializes a new instance of the `MultiDecodeType` class. |

## Properties

| Name | Description |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | Returns a number of single types. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | Adds one more [`SingleDecodeType`](../singledecodetype/) to the MultiDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | Check if this contains all types from barcode types. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | Is contain any of types |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Returns a value indicating whether this instance is equal to a specified [`BaseDecodeType`](../basedecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | Returns a value indicating whether this instance is equal to a specified `MultiDecodeType` value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | Returns a value indicating whether this instance is equal to a specified `MultiDecodeType` value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | Returns a value indicating whether this decode types collection contains only specified [`SingleDecodeType`](../singledecodetype/) value. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Excludes [`SingleDecodeType`](../singledecodetype/) from the MultiDecodeType and returns new MultiDecodeType instance. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Returns the hash code for this instance. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Represents a list of single types. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Overridden method representing MultiDecodeType as a string. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | Converts the string representation of a MultiDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Examples

This sample shows how to create compound MultiDecode types that combine SingleDecodeType and MultiDecode types.

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

### See Also

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



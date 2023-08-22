---
title: Class MultyDecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.MultyDecodeType class. Composite decode type
type: docs
weight: 250
url: /net/aspose.barcode.barcoderecognition/multydecodetype/
---
## MultyDecodeType class

Composite decode type.

```csharp
public class MultyDecodeType : BaseDecodeType, IEquatable<MultyDecodeType>
```

## Constructors

| Name | Description |
| --- | --- |
| [MultyDecodeType](multydecodetype/#constructor)(params BaseDecodeType[]) | Initializes a new instance of the `MultyDecodeType` class. |
| [MultyDecodeType](multydecodetype/#constructor_1)(params SingleDecodeType[]) | Initializes a new instance of the `MultyDecodeType` class. |

## Properties

| Name | Description |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multydecodetype/getsingletypescount/) { get; } | Returns a number of single types. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multydecodetype/add/)(SingleDecodeType) | Adds one more [`SingleDecodeType`](../singledecodetype/) to the MultyDecodeType. |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multydecodetype/containsall/)(params BaseDecodeType[]) | Check if this contains all types from barcode types. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multydecodetype/containsany/)(params BaseDecodeType[]) | Is contain any of types |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Returns a value indicating whether this instance is equal to a specified [`BaseDecodeType`](../basedecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multydecodetype/equals/#equals_1)(MultyDecodeType) | Returns a value indicating whether this instance is equal to a specified `MultyDecodeType` value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multydecodetype/equals/#equals_3)(object) | Returns a value indicating whether this instance is equal to a specified `MultyDecodeType` value. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(SingleDecodeType) | Returns a value indicating whether this instance is equal to a specified [`SingleDecodeType`](../singledecodetype/) value. |
| [Exclude](../../aspose.barcode.barcoderecognition/multydecodetype/exclude/)(SingleDecodeType) | Excludes [`SingleDecodeType`](../singledecodetype/) from the MultyDecodeType and returns new MultyDecodeType instance. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multydecodetype/gethashcode/)() | Returns the hash code for this instance. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multydecodetype/getsingletypes/)() | Represents a list of single types. |
| override [ToString](../../aspose.barcode.barcoderecognition/multydecodetype/tostring/)() | Overridden method representing MultyDecodeType as a string. |
| static [TryParse](../../aspose.barcode.barcoderecognition/multydecodetype/tryparse/)(string, out MultyDecodeType) | Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Examples

This sample shows how to create compound MultyDecode types that combine SingleDecodeType and MultiDecode types.

```csharp
[C#]
MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.Code128, DecodeType.Code39Standard);
[VB.NET]
Dim multyType1 As MultyDecodeType 
multyType1 = New MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multyType2 As MultyDecodeType
multyType2 = New MultyDecodeType(multyType1, DecodeType.Code128, DecodeType.Code39Standard)
```

### See Also

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



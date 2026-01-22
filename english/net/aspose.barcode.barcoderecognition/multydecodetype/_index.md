---
title: Class MultyDecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.MultyDecodeType class. Composite decode type
type: docs
weight: 300
url: /net/aspose.barcode.barcoderecognition/multydecodetype/
---
## MultyDecodeType class

Composite decode type.

```csharp
[Obsolete("Use MultiDecodeType instead")]
public class MultyDecodeType : MultiDecodeType
```

## Constructors

| Name | Description |
| --- | --- |
| [MultyDecodeType](multydecodetype/#constructor)(params BaseDecodeType[]) | Initializes a new instance of the `MultyDecodeType` class. |
| [MultyDecodeType](multydecodetype/#constructor_1)(params SingleDecodeType[]) | Initializes a new instance of the `MultyDecodeType` class. |

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
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/)(MultiDecodeType) | Returns a value indicating whether this instance is equal to a specified [`MultiDecodeType`](../multidecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/)(object) | Returns a value indicating whether this instance is equal to a specified [`MultiDecodeType`](../multidecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/)(SingleDecodeType) | Returns a value indicating whether this decode types collection contains only specified [`SingleDecodeType`](../singledecodetype/) value. |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | Excludes [`SingleDecodeType`](../singledecodetype/) from the MultiDecodeType and returns new MultiDecodeType instance. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | Returns the hash code for this instance. |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | Represents a list of single types. |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | Overridden method representing MultiDecodeType as a string. |

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

* class [MultiDecodeType](../multidecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



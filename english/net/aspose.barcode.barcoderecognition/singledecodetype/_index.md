---
title: Class SingleDecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.SingleDecodeType class. Single decode type. See decode type to get instance
type: docs
weight: 370
url: /net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

Single decode type. See decode type to get instance.

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## Properties

| Name | Description |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | Gets an index of decode type |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | Gets a name of decode type |

## Methods

| Name | Description |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | Converts the string representation of the name of a SingleDecodeType to its instance. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | Returns a value indicating whether this instance is included into the list specified. |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | Returns a value indicating whether this instance is equal to a specified [`BaseDecodeType`](../basedecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | Returns a value indicating whether the specified [`MultiDecodeType`](../multidecodetype/) collection contains only this decode type. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | Returns a value indicating whether this instance is equal to a specified `SingleDecodeType` value. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | Returns a value indicating whether this instance is equal to a specified `SingleDecodeType` value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | Returns the hash code for this instance. |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | Converts the instance of SingleDecodeType to its equivalent string representation. The string format is: "Index:-1; Name:None". |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | Returns the name of the given SingleDecodeType as a string. |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | Converts the instance of SingleDecodeType to its equivalent string representation. The string format is: "Index:-1; Name:None". |

## Examples

This sample shows how to get instance of single decode type.

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### See Also

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



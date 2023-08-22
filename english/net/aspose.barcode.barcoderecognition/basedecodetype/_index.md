---
title: Class BaseDecodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.BarCodeRecognition.BaseDecodeType class. Base class for MultyDecodeType and SingleDecodeType
type: docs
weight: 130
url: /net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

Base class for MultyDecodeType and SingleDecodeType.

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## Methods

| Name | Description |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | Determines whether any of the given decode types is included into |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | Returns a value indicating whether this instance is equal to a specified `BaseDecodeType` value. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultyDecodeType) | Returns a value indicating whether this instance is equal to a specified [`MultyDecodeType`](../multydecodetype/) value. |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | Returns a value indicating whether this instance is equal to a specified `BaseDecodeType` value. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | Returns a value indicating whether this instance is equal to a specified [`SingleDecodeType`](../singledecodetype/) value. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | Returns the hash code for this instance. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | Converts the string representation of a BaseDecodeType to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultyDecodeType) | Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed. |

## Examples

This sample shows how to use BaseDecodeType with SingleDecodeType and MultyDecodeType

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended)
```

### See Also

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: Class SymbologyEncodeType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.SymbologyEncodeType class. Symbology encode type. See EncodeTypes to get instance
type: docs
weight: 1620
url: /net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

Symbology encode type. See EncodeTypes to get instance.

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## Properties

| Name | Description |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | Gets a classification of this symbology. |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | Gets an index of encode type |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | Gets a name of encode type |

## Methods

| Name | Description |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | Returns a value indicating whether this instance is equal to a specified [`BaseEncodeType`](../baseencodetype/) value. |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | Returns a value indicating whether this instance is equal to a specified [`BaseEncodeType`](../baseencodetype/) value. |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | Returns the hash code for this instance. |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | Converts the instance of BaseEncodeType to its equivalent string representation. The string format is: "Index:0; Name:Codabar". |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | Returns the name of the given BaseEncodeType as a string. |

## Examples

This sample shows how to get instance of SymbologyEncodeType class.

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### See Also

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



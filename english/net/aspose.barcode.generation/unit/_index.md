---
title: Class Unit
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.Unit class. Specifies the size value in different units Pixel Inches etc
type: docs
weight: 1650
url: /net/aspose.barcode.generation/unit/
---
## Unit class

Specifies the size value in different units (Pixel, Inches, etc.).

```csharp
public sealed class Unit
```

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Gets or sets size value in document units. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Gets or sets size value in inches. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Gets or sets size value in millimeters. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Gets or sets size value in pixels. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Gets or sets size value in point. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Resolution |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Determines whether this instance and a specified object, which must also be a `Unit` object, have the same value. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Returns the hash code for this object. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Returns a human-readable string representation of this `Unit`. |

## Examples

This sample shows how to create and save a BarCode image.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



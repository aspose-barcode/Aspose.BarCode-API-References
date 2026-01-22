---
title: Class FontUnit
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.FontUnit class. Defines a particular format for text including font face size and style attributes where size in Unit value property
type: docs
weight: 1240
url: /net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Defines a particular format for text, including font face, size, and style attributes where size in Unit value property.

```csharp
public sealed class FontUnit
```

## Properties

| Name | Description |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Gets or sets the face name of this Font. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Gets or sets size of this FontUnit in Unit value. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Gets or sets style information for this FontUnit. |

## Examples

This sample shows how to create and save a BarCode image.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



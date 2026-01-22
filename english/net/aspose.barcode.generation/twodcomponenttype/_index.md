---
title: Enum TwoDComponentType
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.TwoDComponentType enum. Type of 2D component
type: docs
weight: 1640
url: /net/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enumeration

Type of 2D component

```csharp
public enum TwoDComponentType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Auto select type of 2D component |
| CC_A | `1` | CC-A type of 2D component. It is a structural variant of MicroPDF417 |
| CC_B | `2` | CC-B type of 2D component. It is a MicroPDF417 symbol. |
| CC_C | `3` | CC-C type of 2D component. It is a PDF417 symbol. |

## Examples

This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/'

```csharp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
{
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
    
    // Aspect ratio of 2D component
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
        
    // X-Dimension of 1D and 2D components
    generator.Parameters.Barcode.XDimension.Pixels = 3;
        
    // Height of 1D component
    generator.Parameters.Barcode.BarHeight.Pixels = 100;
    
    generator.Save("test.png");
}
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



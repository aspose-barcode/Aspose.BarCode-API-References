---
title:  enum
linktitle: TwoDComponentType
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. Type of 2D component in C++.'
type: docs
weight: 8300
url: /cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


Type of 2D component

```cpp
enum class TwoDComponentType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | Auto select type of 2D component |
| CC_A | 1 | CC-A type of 2D component. It is a structural variant of MicroPDF417 |
| CC_B | 2 | CC-B type of 2D component. It is a MicroPDF417 symbol. |
| CC_C | 3 | CC-C type of 2D component. It is a PDF417 symbol. |

## Remarks


This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' 
```cpp
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

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

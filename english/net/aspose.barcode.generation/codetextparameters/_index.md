---
title: Class CodetextParameters
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.CodetextParameters class. Codetext parameters
type: docs
weight: 1060
url: /net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Codetext parameters.

```csharp
public class CodetextParameters
```

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Gets or sets the alignment of the code text. Default value: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Specify the displaying CodeText's Color. Default value: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.Auto. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.Auto especially in AutoSizeMode.Nearest or AutoSizeMode.Interpolation. Default value: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. Default value: CodeLocation.Below for 1D barcodes and CodeLocation.None for 2D barcodes. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Specify word wraps (line breaks) within text. Default value: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | Space between the CodeText and the BarCode in [`Unit`](../unit/) value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Returns a human-readable string representation of this `CodetextParameters`. |

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



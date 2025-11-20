---
title: Class CodetextParametersUI
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Windows.Forms.CodetextParametersUI class. Codetext parameters
type: docs
weight: 1710
url: /net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Codetext parameters.

```csharp
public class CodetextParametersUI
```

## Properties

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Gets or sets the alignment of the code text. Default value: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Specify the displaying CodeText's Color. Default value: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode.Auto. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode.Auto especially in AutoSizeMode.Nearest or AutoSizeMode.Interpolation. Default value: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. Default value: CodeLocation.Below for 1D barcodes and CodeLocation.None for 2D barcodes. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | Space between the CodeText and the BarCode in [`Unit`](../../aspose.barcode.generation/unit/) value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Returns a human-readable string representation of this [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/). |

### See Also

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)



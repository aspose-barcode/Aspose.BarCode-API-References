---
title: Aspose::BarCode::Generation::CodetextParameters class
linktitle: CodetextParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::CodetextParameters class. Codetext parameters in C++.'
type: docs
weight: 1500
url: /cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Codetext parameters.

```cpp
class CodetextParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Gets the alignment of the code text. Default value: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Specify the displaying CodeText's Color. Default value: Color.Black. |
| [get_Font](./get_font/)() const | Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use [FontMode.Auto](../aztecencodemode/) especially in [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). Default value: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Specify the displaying CodeText Location, set to [CodeLocation.None](../codelocation/) to hide CodeText. Default value: [CodeLocation.Below](../codelocation/) for 1D barcodes and [CodeLocation.None](../codelocation/) for 2D barcodes. |
| [get_NoWrap](./get_nowrap/)() const | Specify word wraps (line breaks) within text. Default value: false. |
| [get_Space](./get_space/)() const | Space between the CodeText and the [BarCode](../../aspose.barcode/) in [Unit ](../unit/) value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Sets the alignment of the code text. Default value: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Specify the displaying CodeText's Color. Default value: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use [FontMode.Auto](../aztecencodemode/) especially in [AutoSizeMode.Nearest](../autosizemode/) or [AutoSizeMode.Interpolation](../autosizemode/). Default value: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Specify the displaying CodeText Location, set to [CodeLocation.None](../codelocation/) to hide CodeText. Default value: [CodeLocation.Below](../codelocation/) for 1D barcodes and [CodeLocation.None](../codelocation/) for 2D barcodes. |
| [set_NoWrap](./set_nowrap/)(bool) | Specify word wraps (line breaks) within text. Default value: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Space between the CodeText and the [BarCode](../../aspose.barcode/) in [Unit ](../unit/) value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [CodetextParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

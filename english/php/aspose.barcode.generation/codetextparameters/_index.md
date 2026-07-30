---
title: "CodetextParameters Class"
linktitle: "CodetextParameters"
articleTitle: "CodetextParameters"
second_title: "Aspose.BarCode for PHP via Java"
description: "Codetext parameters."
type: docs
weight: 10
url: /php/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

**Namespace:** `Aspose.Barcode.Generation`


Codetext parameters.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./codetextparameters/) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [Alignment](./alignment/) | Read/Write | Gets the alignment of the code text. Default value: TextAlignment::CENTER. |
| [Color](./color/) | Read/Write | Specify the displaying CodeText's Color. Default value BLACK. |
| [Font](./font/) | Read/Write | Specify the displaying CodeText's font. Default value: Arial 5pt regular. Ignored if FontMode is set to FontMode::AUTO. |
| [FontMode](./fontmode/) | Read/Write | Specify FontMode. If FontMode is set to Auto, font size will be calculated automatically based on xDimension value. It is recommended to use FontMode::AUTO especially in AutoSizeMode.NEAREST or AutoSizeMode::INTERPOLATION. Default value: FontMode::AUTO. |
| [Location](./location/) | Read/Write | Specify the displaying CodeText Location, set to CodeLocation::NONE to hide CodeText. Default value: CodeLocation::BELOW. |
| [NoWrap](./nowrap/) | Read/Write | Specify word wraps (line breaks) within text. |
| [Space](./space/) | Read/Write | Space between the CodeText and the BarCode in Unit value. Default value: 2pt. Ignored for EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [TwoDDisplayText](./twoddisplaytext/) | Read/Write | Text that will be displayed instead of codetext in 2D barcodes. Used for: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |

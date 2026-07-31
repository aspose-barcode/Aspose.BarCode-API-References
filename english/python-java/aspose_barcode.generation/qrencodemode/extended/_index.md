---
title: "QREncodeMode.EXTENDED"
linktitle: "EXTENDED"
articleTitle: "EXTENDED"
second_title: "Aspose.BarCode for Python via Java"
description: "Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codete"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.qr_encode_mode/qrencodemode/extended/
---

## QREncodeMode.EXTENDED

**Type:** `int`


**Value:** `6`


Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\" must be doubled "\\" in the codetext. FNC1 in first position is set in codetext as as "&lt;FNC1&gt;" FNC1 in second position is set in codetext as as "&lt;FNC1(value)&gt;". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\u001D' If you need to insert "&lt;FNC1&gt;" string into barcode write it as "&lt;\FNC1&gt;" ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. This mode is not supported by MicroQR barcodes.


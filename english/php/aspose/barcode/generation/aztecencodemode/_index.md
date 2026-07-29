---
title: "AztecEncodeMode Enum"
linktitle: "AztecEncodeMode"
articleTitle: "AztecEncodeMode"
second_title: "Aspose.BarCode for PHP via Java"
description: "Encoding mode for Aztec barcodes."
type: docs
weight: 10
url: /php/aspose/barcode/generation/aztecencodemode/
---

## AztecEncodeMode enum

**Namespace:** `Aspose.Barcode.Generation`


Encoding mode for Aztec barcodes.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](/php/aspose/barcode/generation/aztecencodemode/auto/) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BINARY](/php/aspose/barcode/generation/aztecencodemode/binary/) | `4` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [BYTES](/php/aspose/barcode/generation/aztecencodemode/bytes/) | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| [ECI](/php/aspose/barcode/generation/aztecencodemode/eci/) | `5` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| [EXTENDED](/php/aspose/barcode/generation/aztecencodemode/extended/) | `3` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| [EXTENDED_CODETEXT](/php/aspose/barcode/generation/aztecencodemode/extended_codetext/) | `2` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

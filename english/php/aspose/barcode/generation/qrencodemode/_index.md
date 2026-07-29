---
title: "QREncodeMode Enum"
linktitle: "QREncodeMode"
articleTitle: "QREncodeMode"
second_title: "Aspose.BarCode for PHP via Java"
description: "Encoding mode for QR barcodes. This sample shows how to use FNC1 second position in Extended Mode. This sample shows how to use multi ECI mode in Extended Mode."
type: docs
weight: 10
url: /php/aspose/barcode/generation/qrencodemode/
---

## QREncodeMode enum

**Namespace:** `Aspose.Barcode.Generation`


Encoding mode for QR barcodes. This sample shows how to use FNC1 second position in Extended Mode. This sample shows how to use multi ECI mode in Extended Mode.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](/php/aspose/barcode/generation/qrencodemode/auto/) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are encoded in kanji mode if possible, or they are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BINARY](/php/aspose/barcode/generation/qrencodemode/binary/) | `7` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [BYTES](/php/aspose/barcode/generation/qrencodemode/bytes/) | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| [ECI](/php/aspose/barcode/generation/qrencodemode/eci/) | `8` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. This mode is not supported by MicroQR barcodes. |
| [ECI_ENCODING](/php/aspose/barcode/generation/qrencodemode/eci_encoding/) | `4` | Encode codetext with value set in the ECIEncoding property. It can be problems with some old (pre 2006) barcode scanners. This mode is not supported by MicroQR barcodes. |
| [EXTENDED](/php/aspose/barcode/generation/qrencodemode/extended/) | `6` | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\" must be doubled "\\" in the codetext. FNC1 in first position is set in codetext as as "&lt;FNC1&gt;" FNC1 in second position is set in codetext as as "&lt;FNC1(value)&gt;". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\u001D' If you need to insert "&lt;FNC1&gt;" string into barcode write it as "&lt;\FNC1&gt;" ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. This mode is not supported by MicroQR barcodes. |
| [EXTENDED_CODETEXT](/php/aspose/barcode/generation/qrencodemode/extended_codetext/) | `5` | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\" must be doubled "\\" in the codetext. FNC1 in first position is set in codetext as as "&lt;FNC1&gt;" FNC1 in second position is set in codetext as as "&lt;FNC1(value)&gt;". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\u001D' If you need to insert "&lt;FNC1&gt;" string into barcode write it as "&lt;\FNC1&gt;" ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. This mode is not supported by MicroQR barcodes. |
| [UTF_16_BEBOM](/php/aspose/barcode/generation/qrencodemode/utf_16_bebom/) | `3` | Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scanners. |
| [UTF_8_BOM](/php/aspose/barcode/generation/qrencodemode/utf_8_bom/) | `2` | Encode codetext with UTF8 encoding with first ByteOfMark character. |

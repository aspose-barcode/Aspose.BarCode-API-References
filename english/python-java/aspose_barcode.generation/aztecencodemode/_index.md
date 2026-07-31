---
title: "AztecEncodeMode Enum"
linktitle: "AztecEncodeMode"
articleTitle: "AztecEncodeMode"
second_title: "Aspose.BarCode for Python via Java"
description: ""
type: docs
weight: 10
url: /python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/
---

## AztecEncodeMode enum

**Module:** `aspose_barcode.generation.aztec_encode_mode`


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/auto/) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BINARY](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/binary/) | `4` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [BYTES](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/bytes/) | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| [ECI](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/eci/) | `5` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| [EXTENDED](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/extended/) | `3` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| [EXTENDED_CODETEXT](/python-java/aspose_barcode.generation.aztec_encode_mode/aztecencodemode/extended_codetext/) | `2` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

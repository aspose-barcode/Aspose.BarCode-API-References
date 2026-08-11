---
title: "HanXinEncodeMode"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode for Python via Java"
description: "Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters. codetext = \"1234567890ABCDEFGabcdef"
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enum

**Module:** `aspose_barcode.generation.han_xin_encode_mode`


Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters. codetext = "1234567890ABCDEFGabcdefg,Han Xin Code" generator = BarcodeGenerator(EncodeTypes.HAN_XIN, codetext) generator.save(image_path_to_save5, BarCodeImageFormat.BMP) encoded_arr = [0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9] generator = BarcodeGenerator(EncodeTypes.HAN_XIN, None) generator.code_text = encoded_arr generator.parameters.barcode.han_xin.encode_mode = HanXinEncodeMode.BINARY generator.save(image_path_to_save5, BarCodeImageFormat.BMP) codetext = "ΑΒΓΔΕ" generator = BarcodeGenerator(EncodeTypes.HAN_XIN, codetext) generator.parameters.barcode.han_xin.encode_mode = HanXinEncodeMode.ECI generator.parameters.barcode.han_xin.eci_encoding = ECIEncodings.ISO_8859_7 generator.save(image_path_to_save5, BarCodeImageFormat.BMP) codetext = "https://www.test.com/%BC%DE%%%ab/search=test" generator = BarcodeGenerator(EncodeTypes.HAN_XIN, codetext) generator.parameters.barcode.han_xin.encode_mode = HanXinEncodeMode.URI generator.save(image_path_to_save5, BarCodeImageFormat.BMP)


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](#auto) | `0` | Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically. |
| [BINARY](#binary) | `1` | Binary byte mode encodes binary data in any form and encodes them in their binary byte. Every byte in Binary Byte mode is represented by 8 bits. |
| [ECI](#eci) | `2` | Extended Channel Interpretation (ECI) mode. |
| [EXTENDED](#extended) | `5` | Extended mode will allow more flexible combinations of other modes, this mode is currently not implemented. |
| [UNICODE](#unicode) | `3` | Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code. |
| [URI](#uri) | `4` | URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986. |
### HanXinEncodeMode.AUTO {#auto}

**Type:** `int`

**Value:** `0`

Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically.

### HanXinEncodeMode.BINARY {#binary}

**Type:** `int`

**Value:** `1`

Binary byte mode encodes binary data in any form and encodes them in their binary byte. Every byte in Binary Byte mode is represented by 8 bits.

### HanXinEncodeMode.ECI {#eci}

**Type:** `int`

**Value:** `2`

Extended Channel Interpretation (ECI) mode.

### HanXinEncodeMode.EXTENDED {#extended}

**Type:** `int`

**Value:** `5`

Extended mode will allow more flexible combinations of other modes, this mode is currently not implemented.

### HanXinEncodeMode.UNICODE {#unicode}

**Type:** `int`

**Value:** `3`

Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code.

### HanXinEncodeMode.URI {#uri}

**Type:** `int`

**Value:** `4`

URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986.


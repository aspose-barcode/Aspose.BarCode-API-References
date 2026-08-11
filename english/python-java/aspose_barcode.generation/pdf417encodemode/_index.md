---
title: "Pdf417EncodeMode"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for Python via Java"
description: "Pdf417 barcode encode mode."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/pdf417encodemode/
---

## Pdf417EncodeMode enum

**Module:** `aspose_barcode.generation.pdf_417_encode_mode`


Pdf417 barcode encode mode.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [AUTO](#auto) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BINARY](#binary) | `1` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [ECI](#eci) | `2` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| [EXTENDED](#extended) | `3` | Extended mode which supports multi ECI modes. It is better to use Pdf417ExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
### Pdf417EncodeMode.AUTO {#auto}

**Type:** `int`

**Value:** `0`

In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown.

### Pdf417EncodeMode.BINARY {#binary}

**Type:** `int`

**Value:** `1`

In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown.

### Pdf417EncodeMode.ECI {#eci}

**Type:** `int`

**Value:** `2`

In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode.

### Pdf417EncodeMode.EXTENDED {#extended}

**Type:** `int`

**Value:** `3`

Extended mode which supports multi ECI modes. It is better to use Pdf417ExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset.


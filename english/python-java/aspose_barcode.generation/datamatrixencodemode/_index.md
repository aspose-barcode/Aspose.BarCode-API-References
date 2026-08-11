---
title: "DataMatrixEncodeMode"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for Python via Java"
description: "DataMatrix encoder's encoding mode, default to Auto. This sample shows how to do codetext in Extended Mode."
type: docs
weight: 10
url: /python-java/aspose_barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enum

**Module:** `aspose_barcode.generation.data_matrix_encode_mode`


DataMatrix encoder's encoding mode, default to Auto. This sample shows how to do codetext in Extended Mode.


## Enum Values

| Name | Value | Description |
| --- | --- | --- |
| [ANSIX12](#ansix12) | `11` | Uses ANSI X12 encoding. |
| [ASCII](#ascii) | `1` | Encodes one alphanumeric or two numeric characters per byte. |
| [AUTO](#auto) | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| [BASE_256](#base_256) | `14` | Encode 8 bit values. |
| [BINARY](#binary) | `15` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| [BYTES](#bytes) | `6` | Encode 8 bit values. |
| [C40](#c40) | `8` | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| [ECI](#eci) | `16` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| [EDIFACT](#edifact) | `10` | Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| [EXTENDED](#extended) | `13` | ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes () must be doubled in text. |
| [EXTENDED_CODETEXT](#extended_codetext) | `12` | ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes () must be doubled in text. |
| [TEXT](#text) | `9` | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters |
### DataMatrixEncodeMode.ANSIX12 {#ansix12}

**Type:** `int`

**Value:** `11`

Uses ANSI X12 encoding.

### DataMatrixEncodeMode.ASCII {#ascii}

**Type:** `int`

**Value:** `1`

Encodes one alphanumeric or two numeric characters per byte.

### DataMatrixEncodeMode.AUTO {#auto}

**Type:** `int`

**Value:** `0`

In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown.

### DataMatrixEncodeMode.BASE_256 {#base_256}

**Type:** `int`

**Value:** `14`

Encode 8 bit values.

### DataMatrixEncodeMode.BINARY {#binary}

**Type:** `int`

**Value:** `15`

In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown.

### DataMatrixEncodeMode.BYTES {#bytes}

**Type:** `int`

**Value:** `6`

Encode 8 bit values.

### DataMatrixEncodeMode.C40 {#c40}

**Type:** `int`

**Value:** `8`

Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters

### DataMatrixEncodeMode.ECI {#eci}

**Type:** `int`

**Value:** `16`

In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode.

### DataMatrixEncodeMode.EDIFACT {#edifact}

**Type:** `int`

**Value:** `10`

Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters.

### DataMatrixEncodeMode.EXTENDED {#extended}

**Type:** `int`

**Value:** `13`

ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes () must be doubled in text.

### DataMatrixEncodeMode.EXTENDED_CODETEXT {#extended_codetext}

**Type:** `int`

**Value:** `12`

ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. It is better to use DataMatrixExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. Encodation schemes are set in the next format : "\Encodation_scheme_name:text\Encodation_scheme_name:text". Allowed encodation schemes are: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. All backslashes () must be doubled in text.

### DataMatrixEncodeMode.TEXT {#text}

**Type:** `int`

**Value:** `9`

Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters


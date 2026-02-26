---
title: "QREncodeMode Enum"
linktitle: "QREncodeMode"
articleTitle: "QREncodeMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Encoding mode for QR barcodes."
type: docs
weight: 900
url: /nodejs/qrencodemode/
---
## QREncodeMode enumeration

Encoding mode for QR barcodes.

```javascript
public enum QREncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | Encode codetext as is non-unicode charset.  If there is any unicode character,  the codetext will be encoded with value which is set in CodeTextEncoding. |
| BYTES | `1` | Encode codetext as plain bytes. If it detects any unicode character, the character will be encoded as two bytes, lower byte first. |
| UTF_8_BOM | `2` | Encode codetext with UTF8 encoding with first ByteOfMark character. |
| UTF_16_BEBOM | `3` | Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scaners. |
| ECI_ENCODING | `4` | Encode codetext with value set in the ECI_ENCODING property. It can be problems with some old (pre 2006) barcode scaners. |
| EXTENDED_CODETEXT | `5` | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. It is better to use QrExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. Encoding Principles: All symbols "\" must be doubled "\\" in the codetext. FNC1 in first position is set in codetext as as "&lt;FNC1&gt;" FNC1 in second position is set in codetext as as "&lt;FNC1(value)&gt;". The value must be single symbols (a-z, A-Z) or digits from 0 to 99. Group Separator for FNC1 modes is set as 0x1D character '\\u001D'  If you need to insert "&lt;FNC1&gt;" string into barcode write it as "&lt;\FNC1&gt;"  ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier TO disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000" All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

### See Also

* assembly [Aspose.BarCode](../)


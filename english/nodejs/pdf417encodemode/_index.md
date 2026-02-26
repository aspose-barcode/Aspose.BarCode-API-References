---
title: "Pdf417EncodeMode Enum"
linktitle: "Pdf417EncodeMode"
articleTitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Pdf417 barcode encode mode."
type: docs
weight: 1160
url: /nodejs/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 barcode encode mode

```javascript
public enum Pdf417EncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| BINARY | `1` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `2` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| EXTENDED | `3` | Extended mode which supports multi ECI modes. It is better to use Pdf417ExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

### See Also

* assembly [Aspose.BarCode](../)


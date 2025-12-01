---
title: MaxiCodeEncodeMode
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

Encoding mode for MaxiCode barcodes.

## Members
| Member name | Description |
| :- | :- |
|AUTO|In Auto mode, the CodeText is encoded with maximum data compactness. <br/>            Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.|
|BYTES|Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first.|
|EXTENDED_CODETEXT||
|EXTENDED||
|BINARY|In Binary mode, the CodeText is encoded with maximum data compactness. <br/>            If a Unicode character is found, an exception is thrown.|
|ECI|In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.<br/>            Please note that some old (pre 2006) scanners may not support this mode.|

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


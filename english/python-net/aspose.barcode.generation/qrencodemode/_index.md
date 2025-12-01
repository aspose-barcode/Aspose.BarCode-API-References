---
title: QREncodeMode
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Encoding mode for QR barcodes.

## Members
| Member name | Description |
| :- | :- |
|AUTO|In Auto mode, the CodeText is encoded with maximum data compactness. <br/>            Unicode characters are encoded in kanji mode if possible, or they are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.|
|BYTES|Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first.|
|UTF_8BOM|Encode codetext with UTF8 encoding with first ByteOfMark character.|
|UTF_16BEBOM|Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scanners.|
|ECI_ENCODING|Encode codetext with value set in the ECIEncoding property. It can be problems with some old (pre 2006) barcode scanners.<br/>            This mode is not supported by MicroQR barcodes.|
|EXTENDED_CODETEXT||
|EXTENDED||
|BINARY|In Binary mode, the CodeText is encoded with maximum data compactness. <br/>            If a Unicode character is found, an exception is thrown.|
|ECI|In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.<br/>            Please note that some old (pre 2006) scanners may not support this mode.<br/>            This mode is not supported by MicroQR barcodes.|

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


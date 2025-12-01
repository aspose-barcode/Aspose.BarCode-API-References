---
title: DataMatrixEncodeMode
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

DataMatrix encoder's encoding mode, default to Auto

## Members
| Member name | Description |
| :- | :- |
|AUTO|In Auto mode, the CodeText is encoded with maximum data compactness. <br/>            Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.|
|ASCII|Encodes one alphanumeric or two numeric characters per byte|
|BYTES|Encode 8 bit values|
|C40|Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters|
|TEXT|Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters|
|EDIFACT|Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters.|
|ANSIX12|Uses ANSI X12 encoding.|
|EXTENDED_CODETEXT||
|EXTENDED||
|BASE256|Encode 8 bit values|
|BINARY|In Binary mode, the CodeText is encoded with maximum data compactness. <br/>            If a Unicode character is found, an exception is thrown.|
|ECI|In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier.<br/>            If a character is found that is not supported by the selected ECI encoding, an exception is thrown.<br/>            Please note that some old (pre 2006) scanners may not support this mode.|

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


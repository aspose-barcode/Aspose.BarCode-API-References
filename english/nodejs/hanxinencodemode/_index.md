---
title: HanXinEncodeMode Enum
linktitle: HanXinEncodeMode
articleTitle: HanXinEncodeMode
second_title: Aspose.BarCode for Node.js via Java
description: "Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters."
type: docs
weight: 1200
url: /nodejs/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Han Xin Code encoding mode. It is recommended to use Auto with ASCII / Chinese characters or Unicode for Unicode characters.

```javascript
public enum HanXinEncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | Sequence of Numeric, Text, ECI, Binary Bytes and 4 GB18030 modes changing automatically. |
| BINARY | `1` | Binary byte mode encodes binary data in any form and encodes them in their binary byte. Every byte in Binary Byte mode is represented by 8 bits. |
| ECI | `2` | Extended Channel Interpretation (ECI) mode |
| UNICODE | `3` | Unicode mode designs a way to represent any text data reference to UTF8 encoding/charset in Han Xin Code. |
| URI | `4` | URI mode indicates the data represented in Han Xin Code is Uniform Resource Identifier (URI) reference to RFC 3986. |
| EXTENDED | `5` | Extended mode  will allow more flexible combinations of other modes, this mode is currently not implemented. |

## Examples

```javascript
// Auto mode
let codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
let generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

```javascript
// Bytes mode
let encodedArr = [0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9];
//encode array to string
let codetext = "";
for (int i = 0; i <encodedArr.length; i++)
{
let bval = String.fromCharCode(encodedArr[i]);
codetext += bval;
}
let generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BYTES);
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

```javascript
// ECI mode
let codetext = "ΑΒΓΔΕ";
let generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

```javascript
// URI mode
let codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.URI);
generator.save("test.bmp", BarcodeImageFormat.BMP);
// Extended mode - TBD
</pre>
</pre></blockquote></hr></p>
```

### See Also

* assembly [Aspose.BarCode](../)


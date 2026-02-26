---
title: MaxiCodeEncodeMode Enum
linktitle: MaxiCodeEncodeMode
articleTitle: MaxiCodeEncodeMode
second_title: Aspose.BarCode for Node.js via Java
description: "Encoding mode for MaxiCode barcodes."
type: docs
weight: 1130
url: /nodejs/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

Encoding mode for MaxiCode barcodes.

```javascript
public enum MaxiCodeEncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| BYTES | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| EXTENDED_CODETEXT | `2` | Extended mode which supports multi ECI modes. It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| EXTENDED | `3` | Extended mode which supports multi ECI modes. It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| BINARY | `4` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `5` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |

## Examples

```javascript
//Auto mode
let codetext = "犬Right狗";
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext));
generator.getParameters().getBarcode().getMaxiCode().setECIEncoding(ECIEncodings.UTF8);
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

```javascript
//Bytes mode
let encodedArr = [ 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 ];
//encode array to string
let strBld = "";
for(let i = 0; i < encodedArr.length; i++)
{
let bval = encodedArr[i];
strBld += bval;
}
let codetext = strBld;
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext))
generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.BYTES);
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

```javascript
//Extended codetext mode
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
// generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext);
generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.EXTENDED_CODETEXT);
generator.getParameters().getBarcode().getMaxiCode().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

### See Also

* assembly [Aspose.BarCode](../)


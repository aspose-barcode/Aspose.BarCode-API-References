---
title: DotCodeEncodeMode Enum
linktitle: DotCodeEncodeMode
articleTitle: DotCodeEncodeMode
second_title: Aspose.BarCode for Node.js via Java
description: Encoding mode for DotCode barcodes.
type: docs
weight: 1150
url: /nodejs/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Encoding mode for DotCode barcodes.

```javascript
public enum DotCodeEncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| BYTES | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| EXTENDED_CODETEXT | `2` | Extended mode which supports multi ECI modes. It is better to use DotCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| BINARY | `3` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `4` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |
| EXTENDED | `5` | Extended mode which supports multi ECI modes. It is better to use DotCodeExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

## Examples

```javascript
//Auto mode with macros
let codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

```javascript
//Auto mode
let codetext = "犬Right狗";
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setECIEncoding(ECIEncodings.UTF8);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

```javascript
//Bytes mode
let encodedArr = array( 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 );
//encode array to string
let codetext = "";
for(let i = 0; i < encodedArr.length; i++)
{
let bval = encodedArr[i];
codetext += bval;
};
```

```javascript
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.BYTES);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

```javascript
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

### See Also

* assembly [Aspose.BarCode](../)


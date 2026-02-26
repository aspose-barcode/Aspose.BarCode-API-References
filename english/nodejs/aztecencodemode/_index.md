---
title: AztecEncodeMode Enum
linktitle: AztecEncodeMode
articleTitle: AztecEncodeMode
second_title: Aspose.BarCode for Node.js via Java
description: Encoding mode for Aztec barcodes.
type: docs
weight: 1220
url: /nodejs/aztecencodemode/
---
## AztecEncodeMode enumeration

Encoding mode for Aztec barcodes.

```javascript
public enum AztecEncodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| AUTO | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| BYTES | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| EXTENDED_CODETEXT | `2` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| EXTENDED | `3` | Extended mode which supports multi ECI modes. It is better to use AztecExtCodetextBuilder for extended codetext generation. Use Display2DText property to set visible text to removing managing characters. ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier All unicode characters after ECI identifier are automatically encoded into correct character codeset. |
| BINARY | `4` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `5` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |

## Examples

```javascript
//Auto mode
let codetext = "犬Right狗";
let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
generator.getParameters().getBarcode().getAztec().setECIEncoding(ECIEncodings.UTF_8);
generator.save("test.bmp");
```

```javascript
//Bytes mode
let encodedArr = [ 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 ];
//encode array to string
let strBld = "";
for(let i = 0; i < encodedArr; i++)
{
byte bval = encodedArr[i]
strBld.append(String.fromCharCode(bval));
}
let codetext = strBld;
let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.BYTES);
generator.save("test.bmp", BarcodeImageFormat.PNG);
```

```javascript
//Extended codetext mode
//create codetext
let textBuilder = new AztecExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.EXTENDED_CODETEXT);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.PNG);
</pre>
</pre></blockquote></hr></p>
```

### See Also

* assembly [Aspose.BarCode](../)


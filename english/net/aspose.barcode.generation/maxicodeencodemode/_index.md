---
title: Enum MaxiCodeEncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.MaxiCodeEncodeMode enum. Encoding mode for MaxiCode barcodes
type: docs
weight: 1130
url: /net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

Encoding mode for MaxiCode barcodes.

```csharp
public enum MaxiCodeEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Encode codetext with value set in the ECIEncoding property. |
| Bytes | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| ExtendedCodetext | `2` | Extended mode which supports multi ECI modes.<br>It is better to use MaxiCodeExtCodetextBuilder for extended codetext generation.<br>Use Display2DText property to set visible text to removing managing characters.<br>ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier<br>All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

## Examples

```csharp
[C#]
//Auto mode
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes mode
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

//encode array to string
StringBuilder strBld = new StringBuilder();
foreach (byte bval in encodedArr)
    strBld.Append((char) bval);
var codetext = strBld.ToString();

using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Bytes;
    generator.Save("test.bmp");
}

//Extended codetext mode
//create codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



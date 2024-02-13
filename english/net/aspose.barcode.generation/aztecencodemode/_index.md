---
title: Enum AztecEncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.AztecEncodeMode enum. Encoding mode for Aztec barcodes
type: docs
weight: 730
url: /net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Encoding mode for Aztec barcodes.

```csharp
public enum AztecEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Encode codetext with value set in the ECIEncoding property. |
| Bytes | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| ExtendedCodetext | `2` | Extended mode which supports multi ECI modes. |

## Examples

```csharp
[C#]
//Auto mode
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes mode
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

//encode array to string
StringBuilder strBld = new StringBuilder();
foreach (byte bval in encodedArr)
    strBld.Append((char) bval);
var codetext = strBld.ToString();

using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Bytes;
    generator.Save("test.bmp");
}

//Extended codetext mode
//create codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



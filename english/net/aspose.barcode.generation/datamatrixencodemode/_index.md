---
title: Enum DataMatrixEncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DataMatrixEncodeMode enum. DataMatrix encoders encoding mode default to Auto
type: docs
weight: 940
url: /net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

DataMatrix encoder's encoding mode, default to Auto

```csharp
public enum DataMatrixEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Automatically pick up the best encode mode for Datamatrix encoding |
| ASCII | `1` | Encodes one alphanumeric or two numeric characters per byte |
| Bytes | `6` | Encode 8 bit values |
| C40 | `8` | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| Text | `9` | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters |
| EDIFACT | `10` | Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| ANSIX12 | `11` | Uses ANSI X12 encoding. |
| ExtendedCodetext | `12` | ExtendedCodetext mode allows to manually switch encodation schemes and ECI encodings in codetext. |

## Examples

This sample shows how to do codetext in Extended Mode.

```csharp
[C#]
//Auto mode
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes mode
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };

//encode array to string
StringBuilder strBld = new StringBuilder();
foreach (byte bval in encodedArr)
    strBld.Append((char) bval);
string codetext = strBld.ToString();

using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.DataMatrixEncodeMode = DataMatrixEncodeMode.Bytes;
    generator.Save("test.bmp");
}


//Extended codetext mode
//create codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(DataMatrixEncodeMode.C40, "ABCDE");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.DataMatrixEncodeMode = DataMatrixEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



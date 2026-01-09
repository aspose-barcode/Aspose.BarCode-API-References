---
title:  enum
linktitle: DataMatrixEncodeMode
second_title: Aspose.BarCode for C++ API Reference
description: ' enum. DataMatrix encoder''s encoding mode, default to Auto in C++.'
type: docs
weight: 5800
url: /cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix encoder's encoding mode, default to Auto

```cpp
enum class DataMatrixEncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | 0 | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| ASCII | 1 | Encodes one alphanumeric or two numeric characters per byte |
| Bytes | 6 | Encode 8 bit values |
| C40 | 8 | Uses C40 encoding. Encodes Upper-case alphanumeric, Lower case and special characters |
| Text | 9 | Uses Text encoding. Encodes Lower-case alphanumeric, Upper case and special characters |
| EDIFACT | 10 | Uses EDIFACT encoding. Uses six bits per character, encodes digits, upper-case letters, and many punctuation marks, but has no support for lower-case letters. |
| ANSIX12 | 11 | Uses ANSI X12 encoding. |
| ExtendedCodetext | 12 |  |
| Extended | 13 |  |
| Base256 | 14 | Encode 8 bit values |
| Binary | 15 | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | 16 | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. |

## Remarks


This sample shows how to do codetext in Extended Mode. 
```cpp
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
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Extended codetext mode
//create codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    
<br>
//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

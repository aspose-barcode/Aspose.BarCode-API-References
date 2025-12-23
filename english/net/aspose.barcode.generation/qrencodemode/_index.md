---
title: Enum QREncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QREncodeMode enum. Encoding mode for QR barcodes
type: docs
weight: 1480
url: /net/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enumeration

Encoding mode for QR barcodes.

```csharp
public enum QREncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | In Auto mode, the CodeText is encoded with maximum data compactness. Unicode characters are encoded in kanji mode if possible, or they are re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. |
| Bytes | `1` | *This property is obsolete and will be removed in future releases. Instead, use the 'SetCodeText' method to convert the message to byte array with specified encoding.* Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| Utf8BOM | `2` | *This property is obsolete and will be removed in future releases. Instead, use the 'SetCodeText' method with UTF8 encoding to add a byte order mark (BOM) and encode the message. After that, the CodeText can be encoded using the 'Auto' mode.* Encode codetext with UTF8 encoding with first ByteOfMark character. |
| Utf16BEBOM | `3` | *This property is obsolete and will be removed in future releases. Instead, use the 'SetCodeText' method with BigEndianUnicode encoding to add a byte order mark (BOM) and encode the message. After that, the CodeText can be encoded using the 'Auto' mode.* Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scanners. |
| ECIEncoding | `4` | *This property is obsolete and will be removed in future releases. Instead, use ECI option.* Encode codetext with value set in the ECIEncoding property. It can be problems with some old (pre 2006) barcode scanners. This mode is not supported by MicroQR barcodes. |
| ExtendedCodetext | `5` | *This property is obsolete and will be removed in future releases. Instead, use the 'Extended' encode mode.* Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. |
| Extended | `6` | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes. |
| Binary | `7` | In Binary mode, the CodeText is encoded with maximum data compactness. If a Unicode character is found, an exception is thrown. |
| ECI | `8` | In ECI mode, the entire message is re-encoded in the ECIEncoding specified encoding with the insertion of an ECI identifier. If a character is found that is not supported by the selected ECI encoding, an exception is thrown. Please note that some old (pre 2006) scanners may not support this mode. This mode is not supported by MicroQR barcodes. |

## Examples

These samples show how to encode and save QR barcode with extended data formats.

```csharp
//This sample shows how to use ECI encoding and save a BarCode image.

[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8
    generator.Save("test.png")
End Using

//This sample shows how to use FNC1 first position in Extended Mode.

//Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
//It is better to use QrExtCodetextBuilder for extended codetext generation.
//Use Display2DText property to set visible text to removing managing characters.
//Encoding Principles:
//All symbols "\" must be doubled "\\" in the codetext.
//FNC1 in first position is set in codetext as as "<FNC1>"
//FNC1 in second position is set in codetext as as "<FNC1(value)>". The value must be single symbols (a-z, A-Z) or digits from 0 to 99.
//Group Separator for FNC1 modes is set as 0x1D character '\\u001D'
//If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>"
//ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier
//To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000"
//All unicode characters after ECI identifier are automatically encoded into correct character codeset.

[C#]
//create codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//generate barcode
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
[VB.NET]
'create codetext
Dim textBuilder As New QrExtCodetextBuilder()
textBuilder.AddFNC1FirstPosition()
textBuilder.AddPlainCodetext("000%89%%0")
textBuilder.AddFNC1GroupSeparator()
textBuilder.AddPlainCodetext("12345<FNC1>")
'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using

//This sample shows how to use FNC1 second position in Extended Mode.

[C#]
//create codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456"); 
//generate barcode
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
[VB.NET]
'create codetext
Dim textBuilder As New QrExtCodetextBuilder()
textBuilder.AddFNC1SecondPosition("12")
textBuilder.AddPlainCodetext("TRUE3456")
'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using

//This sample shows how to use multi ECI mode in Extended Mode.

[C#]
//create codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");   
//generate barcode
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extendedt;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
[VB.NET]
'create codetext
Dim textBuilder As New QrExtCodetextBuilder()
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will")
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right")
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power")
textBuilder.AddPlainCodetext(@"t\e\\st") 
'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using   
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



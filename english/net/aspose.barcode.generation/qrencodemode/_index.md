---
title: Enum QREncodeMode
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QREncodeMode enum. Encoding mode for QR barcodes. It is recommended to Use Auto with CodeTextEncoding  Encoding.UTF8 for Latin symbols or digits and Utf8BOM for Unicode symbols
type: docs
weight: 1250
url: /net/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enumeration

Encoding mode for QR barcodes. It is recommended to Use Auto with CodeTextEncoding = Encoding.UTF8 for Latin symbols or digits and Utf8BOM for Unicode symbols.

```csharp
public enum QREncodeMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Encode codetext as is non-Unicode charset. If there is any Unicode character, the codetext will be encoded with value which is set in CodeTextEncoding. |
| Bytes | `1` | Encode codetext as plain bytes. If it detects any Unicode character, the character will be encoded as two bytes, lower byte first. |
| Utf8BOM | `2` | Encode codetext with UTF8 encoding with first ByteOfMark character. |
| Utf16BEBOM | `3` | Encode codetext with UTF8 encoding with first ByteOfMark character. It can be problems with some barcode scanners. |
| ECIEncoding | `4` | Encode codetext with value set in the ECIEncoding property. It can be problems with some old (pre 2006) barcode scanners. |
| ExtendedCodetext | `5` | Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.<br>It is better to use QrExtCodetextBuilder for extended codetext generation.<br>Use Display2DText property to set visible text to removing managing characters.<br>Encoding Principles:<br>All symbols "\" must be doubled "\\" in the codetext.<br>FNC1 in first position is set in codetext as as "&lt;FNC1&gt;"<br>FNC1 in second position is set in codetext as as "&lt;FNC1(value)&gt;". The value must be single symbols (a-z, A-Z) or digits from 0 to 99.<br>Group Separator for FNC1 modes is set as 0x1D character '\\u001D'<br>If you need to insert "&lt;FNC1&gt;" string into barcode write it as "&lt;\FNC1&gt;"<br>ECI identifiers are set as single slash and six digits identifier "\000026" - UTF8 ECI identifier<br>To disable current ECI mode and convert to default JIS8 mode zero mode ECI indetifier is set. "\000000"<br>All unicode characters after ECI identifier are automatically encoded into correct character codeset. |

## Examples

These samples show how to encode and save QR barcode with extended data formats.

```csharp
//This sample shows how to use ECI encoding and save a BarCode image.

[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR;
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
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
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using   
```

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



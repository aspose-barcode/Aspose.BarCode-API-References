---
title: "열거형 QREncodeMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.QREncodeMode 열거형. QR 바코드의 인코딩 모드"
type: docs
weight: 1600
url: /ko/net/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enumeration

QR 바코드의 인코딩 모드.

```csharp
public enum QREncodeMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 자동 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자는 가능한 경우 한자 모드로 인코딩되며, 그렇지 않으면 ECI 식별자를 삽입하여 지정된 ECIEncoding으로 다시 인코딩됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자를 발견하면 예외가 발생합니다. |
| Extended | `6` | FNC1 첫 번째 위치, FNC1 두 번째 위치 및 다중 ECI 모드를 지원하는 확장 채널 모드. |
| Binary | `7` | Binary 모드에서는 CodeText가 최대 데이터 압축으로 인코딩됩니다. 유니코드 문자가 발견되면 예외가 발생합니다. |
| ECI | `8` | ECI 모드에서는 전체 메시지가 지정된 ECIEncoding 인코딩으로 재인코딩되며 ECI 식별자가 삽입됩니다. 선택된 ECI 인코딩에서 지원되지 않는 문자가 발견되면 예외가 발생합니다. 일부 오래된(2006년 이전) 스캐너는 이 모드를 지원하지 않을 수 있습니다. 이 모드는 MicroQR 바코드에서 지원되지 않습니다. |

## 예제

이 샘플들은 확장 데이터 형식으로 QR 바코드를 인코딩하고 저장하는 방법을 보여줍니다.

```csharp
//이 샘플은 ECI 인코딩을 사용하는 방법과 BarCode 이미지를 저장하는 방법을 보여줍니다.

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

//이 샘플은 확장 모드에서 FNC1 첫 번째 위치를 사용하는 방법을 보여줍니다.

Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
It is better to use QrExtCodetextBuilder for extended codetext generation.
Use Display2DText property to set visible text by removing managing characters.
Encoding Principles:
All symbols "\" must be doubled "\\" in the codetext.
FNC1 in first position is set in codetext as "<FNC1>".
FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
Group Separator for FNC1 modes is set as 0x1D character '\u001D'.
If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
To switch from another ECI mode to the default ECI mode, use "\000003".
All unicode characters after ECI identifier are automatically encoded into correct character codeset.
QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
"\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
The default compaction mode is "\auto".
Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
This mode is not supported by MicroQR barcodes.

[C#]
//코덱텍스트 생성
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//바코드 생성
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

//이 샘플은 확장 모드에서 FNC1 두 번째 위치를 사용하는 방법을 보여줍니다.

[C#]
//코덱텍스트 생성
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456"); 
//바코드 생성
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

//이 샘플은 확장 모드에서 다중 ECI 모드를 사용하는 방법을 보여줍니다.

[C#]
//코덱텍스트 생성
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");
textBuilder.AddAlphaNumericCodetext(@"ASPOSE2001");
textBuilder.AddNumericCodetext(@"20012026");

//바코드 생성
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
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will")
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right")
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power")
textBuilder.AddPlainCodetext(@"t\e\\st") 
textBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
textBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using   
```

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



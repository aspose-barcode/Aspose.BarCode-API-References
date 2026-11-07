---
title: "enum"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " enum. Режим кодирования для QR‑штрих‑кодов на C++."
type: docs
weight: 8100
url: /ru/cpp/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enum


Режим кодирования для штрих‑кодов QR.

```cpp
enum class QREncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Авто | 0 | В режиме Auto текст CodeText кодируется с максимальной компактностью данных. Символы Unicode кодируются в режиме kanji, если это возможно, либо они перекодируются в указанной кодировке ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| Расширенный | 6 |  |
| Бинарный | 7 | В бинарном режиме текст кода (CodeText) кодируется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | 8 | В режиме ECI все сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые (до 2006) сканеры могут не поддерживать этот режим. Этот режим не поддерживается штрих‑кодами MicroQR. |

## Примечания


Эти примеры показывают, как кодировать и сохранять QR‑штрих-код с расширенными форматами данных.
```cpp
//Этот пример показывает, как использовать кодировку ECI и сохранить изображение BarCode.

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

//Этот пример показывает, как использовать первое положение FNC1 в расширенном режиме.

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
//создать текст кода
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//создать штрих-код
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

//Этот пример показывает, как использовать второе положение FNC1 в расширенном режиме.

[C#]
//создать текст кода
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456");
//создать штрих-код
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

//Этот пример показывает, как использовать многократный режим ECI в расширенном режиме.

[C#]
//создать текст кода
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");
textBuilder.AddAlphaNumericCodetext(@"ASPOSE2001");
textBuilder.AddNumericCodetext(@"20012026");

//создать штрих-код
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
@verbatim
'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using
```

## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

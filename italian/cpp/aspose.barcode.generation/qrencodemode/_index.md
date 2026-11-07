---
title: "enum"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità di codifica per i codici a barre QR in C++."
type: docs
weight: 8100
url: /it/cpp/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enum


Modalità di codifica per i codici a barre QR.

```cpp
enum class QREncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono codificati in modalità kanji se possibile, oppure vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. |
| Esteso | 6 |  |
| Binario | 7 | In modalità Binario, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | 8 | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si noti che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. Questa modalità non è supportata dai codici a barre MicroQR. |

## Osservazioni


Questi esempi mostrano come codificare e salvare il codice a barre QR con formati di dati estesi.
```cpp
//Questo esempio mostra come utilizzare la codifica ECI e salvare un'immagine di BarCode.

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

//Questo esempio mostra come utilizzare la prima posizione FNC1 in Modalità Estesa.

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
//crea codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//genera codice a barre
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

//Questo esempio mostra come utilizzare la seconda posizione FNC1 in Modalità Estesa.

[C#]
//crea codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456");
//genera codice a barre
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

//Questo esempio mostra come utilizzare la modalità multi ECI in Modalità Estesa.

[C#]
//crea codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");
textBuilder.AddAlphaNumericCodetext(@"ASPOSE2001");
textBuilder.AddNumericCodetext(@"20012026");

//genera codice a barre
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

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

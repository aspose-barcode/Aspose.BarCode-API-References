---
title: "Énumération QREncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Énumération Aspose.BarCode.Generation.QREncodeMode. Mode d'encodage pour les codes QR"
type: docs
weight: 1600
url: /fr/net/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enumeration

Mode d'encodage pour les codes-barres QR.

```csharp
public enum QREncodeMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Auto | `0` | En mode Auto, le `CodeText` est encodé avec une compacité maximale des données. Les caractères Unicode sont encodés en mode kanji si possible, ou ils sont réencodés dans l'encodage spécifié par `ECIEncoding` avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. |
| Extended | `6` | Mode Canal étendu qui prend en charge la première position FNC1, la deuxième position FNC1 et les modes ECI multiples. |
| Binary | `7` | En mode Binaire, le CodeText est encodé avec une compacité maximale des données. Si un caractère Unicode est trouvé, une exception est levée. |
| ECI | `8` | In ECI mode, le message complet est ré-encodé dans l'encodage ECIEncoding spécifié avec l'insertion d'un identifiant ECI. Si un caractère est trouvé qui n'est pas pris en charge par l'encodage ECI sélectionné, une exception est levée. Veuillez noter que certains anciens scanners (pré 2006) peuvent ne pas prendre en charge ce mode. Ce mode n'est pas pris en charge par les codes-barres MicroQR. |

## Exemples

Ces exemples montrent comment encoder et enregistrer un code QR avec des formats de données étendus.

```csharp
//Cet exemple montre comment utiliser l'encodage ECI et enregistrer une image de BarCode.

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

//Cet exemple montre comment utiliser la première position FNC1 en mode étendu.

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
//créer du codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//générer le code-barres
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

//Cet exemple montre comment utiliser la deuxième position FNC1 en mode étendu.

[C#]
//créer du codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456"); 
//générer le code-barres
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

//Cet exemple montre comment utiliser le mode multi‑ECI en mode étendu.

[C#]
//créer du codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");
textBuilder.AddAlphaNumericCodetext(@"ASPOSE2001");
textBuilder.AddNumericCodetext(@"20012026");

//générer le code-barres
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

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Klasse QrExtCodetextBuilder"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder Klasse. Erweiterter Codetext-Generator für 2D‑QR‑Barcodes für den ExtendedCodetext‑Modus von EncodeMode"
type: docs
weight: 1630
url: /de/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Erweiterter Codetext-Generator für 2D QR-Barcodes für ExtendedCodetext Mode von EncodeMode

Verwenden Sie die Eigenschaft TwoDDisplayText von BarcodeGenerator, um den sichtbaren Text festzulegen, indem verwaltende Zeichen entfernt werden.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Fügt dem erweiterten Codetext‑Elemente Codetext mit dem angegebenen QR‑Komprimierungsmodus hinzu. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Fügt Codetext mit Extended Channel Identifier hinzu |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Setzt FNC1 an der ersten Position. Wenn zuvor ein anderer FNC1‑Modus gesetzt war, wird er ersetzt. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Fügt dem erweiterten Codetext‑Elemente den Gruppentrennzeichen (GS - '\\u001D') hinzu |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Setzt FNC1 an der zweiten Position. Wenn zuvor ein anderer FNC1‑Modus gesetzt war, wird er ersetzt. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste. |

## Beispiele

Dieses Beispiel zeigt, wie man die erste Position von FNC1 im erweiterten Modus verwendet.

```csharp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Dieses Beispiel zeigt, wie man die zweite Position von FNC1 im erweiterten Modus verwendet.

```csharp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Dieses Beispiel zeigt, wie man den Multi‑ECI‑Modus im erweiterten Modus verwendet.

```csharp
[C#]
//Codetext erstellen
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//Codetext generieren
string codetext = TextBuilder.GetExtendedCodetext();

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Siehe auch

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



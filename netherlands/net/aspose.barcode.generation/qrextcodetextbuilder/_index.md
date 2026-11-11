---
title: "Klasse QrExtCodetextBuilder"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder klasse. Uitgebreide codetextgenerator voor 2D QR-streepjescodes voor ExtendedCodetext-modus van EncodeMode"
type: docs
weight: 1630
url: /nl/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Uitgebreide codetekstgenerator voor 2D QR-barcodes voor ExtendedCodetext Mode van EncodeMode

Gebruik de TwoDDisplayText-eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen door beheertekens te verwijderen.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Voegt codetext toe met de opgegeven QR-compressiemodus aan de uitgebreide codetextitems. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Voegt codetext toe met Extended Channel Identifier |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Stelt FNC1 in de eerste positie in. Als een andere FNC1-modus eerder was ingesteld, wordt deze vervangen. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Voegt Groepsscheidingsteken (GS - "\\u001D") toe aan de uitgebreide codetextitems |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Stelt FNC1 in de tweede positie in. Als een andere FNC1-modus eerder was ingesteld, wordt deze vervangen. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Voegt platte codetext toe aan de uitgebreide codetextitems |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Leegt uitgebreide codetextitems |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Genereert Extended codetext uit de uitgebreide codetextlijst. |

## Voorbeelden

Dit voorbeeld laat zien hoe je FNC1 op de eerste positie in Extended Mode gebruikt.

```csharp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Dit voorbeeld laat zien hoe je FNC1 op de tweede positie in Extended Mode gebruikt.

```csharp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Dit voorbeeld laat zien hoe je multi‑ECI‑modus in Extended Mode gebruikt.

```csharp
[C#]
//codetext maken
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//codetext genereren
string codetext = TextBuilder.GetExtendedCodetext();

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Zie ook

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



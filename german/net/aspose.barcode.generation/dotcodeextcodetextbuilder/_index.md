---
title: "Klasse DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder Klasse. Erweiterter Codetext‑Generator für 2D‑DotCode‑Barcodes für den ExtendedCodetext‑Modus von DotCodeEncodeMode."
type: docs
weight: 1250
url: /de/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Erweiterter Codetext-Generator für 2D DotCode-Barcodes für ExtendedCodetext Mode von DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Fügt Codetext mit Extended Channel Identifier hinzu |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Fügt den FNC1‑Formatbezeichner zu den erweiterten Codetext‑Elementen hinzu |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Fügt die FNC3‑Leserinitialisierung zu den erweiterten Codetext‑Elementen hinzu |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Fügt den FNC3‑Symboltrenner zu den erweiterten Codetext‑Elementen hinzu |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Fügt den strukturierten Anfügemodus zu den erweiterten Codetext‑Elementen hinzu |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste. |

## Beispiele

```csharp
[C#]
//Extended-Codetext-Modus
//Codetext erstellen
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();    

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Siehe auch

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Klass DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder klass. Utökad kodtextgenerator för 2D DotCode-streckkoder för ExtendedCodetext läge i DotCodeEncodeMode."
type: docs
weight: 1250
url: /sv/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Utökad kodtextgenerator för 2D DotCode-streckkoder för ExtendedCodetext läge i DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Lägger till kodtext med Extended Channel Identifier |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Lägger till FNC1-formatidentifierare till de utökade kodtextobjekten |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Lägger till FNC3-läsarinitialisering till de utökade kodtextobjekten |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Lägger till FNC3-symbolseparator till de utökade kodtextobjekten |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Lägger till strukturerat tilläggsläge till de utökade kodtextobjekten |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Rensar de utökade kodtextobjekten |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Genererar Extended kodtext från den utökade kodtextlistan. |

## Exempel

```csharp
[C#]
//Extended kodtextläge
//skapa kodtext
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

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();    

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Se även

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Classe DotCodeExtCodetextBuilder"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Classe Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. Generatore di codetext esteso per codici a barre 2D DotCode per la modalità ExtendedCodetext di DotCodeEncodeMode"
type: docs
weight: 1250
url: /it/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Generatore di codetext esteso per codici a barre 2D DotCode per la modalità ExtendedCodetext di DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Aggiunge il codetext con Identificatore di Canale Esteso |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Aggiunge l'identificatore di formato FNC1 agli elementi di codetext esteso |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext esteso |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Aggiunge il separatore di simboli FNC3 agli elementi codetext estesi |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Aggiunge il codetext semplice agli elementi di codetext esteso |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Aggiunge la modalità di aggiunta strutturata agli elementi codetext estesi |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Cancella gli elementi di codetext esteso |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Genera il codetext esteso dall'elenco di codetext esteso. |

## Esempi

```csharp
[C#]
//Modalità codetext esteso
//crea codetext
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

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();    

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Vedi anche

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



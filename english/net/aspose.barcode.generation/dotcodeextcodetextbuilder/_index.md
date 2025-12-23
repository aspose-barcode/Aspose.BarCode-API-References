---
title: Class DotCodeExtCodetextBuilder
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DotCodeExtCodetextBuilder class. Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode
type: docs
weight: 1150
url: /net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Adds codetext with Extended Channel Identifier |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Adds FNC1 format identifier to the extended codetext items |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Adds FNC3 reader initialization to the extended codetext items |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Adds FNC3 symbol separator to the extended codetext items |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Adds plain codetext to the extended codetext items |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Adds structured append mode to the extended codetext items |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Clears extended codetext items |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Generates Extended codetext from the extended codetext list. |

## Examples

```csharp
[C#]
//Extended codetext mode
//create codetext
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

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### See Also

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



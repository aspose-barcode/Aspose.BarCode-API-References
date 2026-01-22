---
title: Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class
linktitle: DotCodeExtCodetextBuilder
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class in C++.'
type: docs
weight: 2000
url: /cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Description |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Adds codetext with Extended Channel Identifier |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Adds FNC1 format identifier to the extended codetext items |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Adds FNC3 reader initialization to the extended codetext items |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Adds FNC3 symbol separator to the extended codetext items |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Adds plain codetext to the extended codetext items |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Adds structured append mode to the extended codetext items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Clears extended codetext items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generates Extended codetext from the extended codetext list. |
## Remarks


Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode





```cpp
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
<br>
//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## See Also

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

---
title: Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder class
linktitle: MaxiCodeExtCodetextBuilder
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder class in C++.'
type: docs
weight: 3200
url: /cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Description |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Adds codetext with Extended Channel Identifier |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Adds plain codetext to the extended codetext items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Clears extended codetext items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generates Extended codetext from the extended codetext list. |
## Remarks


Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode




Use TwoDDisplayText property of [BarcodeGenerator](../barcodegenerator/) to set visible text to removing managing characters.




This sample shows how to use [MaxiCodeExtCodetextBuilder](./) in Extended Mode. 
```cpp
[C#]
//create codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    
<br>
//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## See Also

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

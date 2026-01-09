---
title: Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder class
linktitle: DataMatrixExtCodetextBuilder
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder class in C++.'
type: docs
weight: 1800
url: /cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Description |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Adds codetext with defined encode mode to the extended codetext items |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Adds codetext with Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Adds codetext with Extended Channel Identifier with defined encode mode |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Adds plain codetext to the extended codetext items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Clears extended codetext items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generates Extended codetext from the extended codetext list. |
## Remarks


Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of EncodeMode





```cpp
[C#]
//Extended codetext mode

//create codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generate codetext
string codetext = textBuilder.GetExtendedCodetext();    
<br>
//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## See Also

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

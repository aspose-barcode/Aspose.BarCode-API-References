---
title: Class DataMatrixExtCodetextBuilder
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder class. Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of EncodeMode
type: docs
weight: 1110
url: /net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Extended codetext generator for 2D DataMatrix barcodes for ExtendedCodetext Mode of EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Adds codetext with defined encode mode to the extended codetext items |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Adds codetext with Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Adds codetext with Extended Channel Identifier with defined encode mode |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Adds plain codetext to the extended codetext items |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Clears extended codetext items |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Generates Extended codetext from the extended codetext list. |

## Examples

```csharp
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

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### See Also

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



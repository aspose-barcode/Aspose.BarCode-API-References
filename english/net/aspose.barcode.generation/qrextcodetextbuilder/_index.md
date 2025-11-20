---
title: Class QrExtCodetextBuilder
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.QrExtCodetextBuilder class. Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode
type: docs
weight: 1530
url: /net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode

Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Adds codetext with Extended Channel Identifier |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Adds FNC1 in first position to the extended codetext items |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Adds Group Separator (GS - '\\u001D') to the extended codetext items |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Adds FNC1 in second position to the extended codetext items |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Adds plain codetext to the extended codetext items |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Clears extended codetext items |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Generates Extended codetext from the extended codetext list. |

## Examples

This sample shows how to use FNC1 first position in Extended Mode.

```csharp
[C#]
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
lTextBuilder.AddFNC1FirstPosition();
lTextBuilder.AddPlainCodetext("000%89%%0");
lTextBuilder.AddFNC1GroupSeparator();
lTextBuilder.AddPlainCodetext("12345<FNC1>");

//generate codetext
string lCodetext = lTextBuilder.GetExtendedCodetext();

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

This sample shows how to use FNC1 second position in Extended Mode.

```csharp
[C#]
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//generate codetext
string lCodetext = lTextBuilder.GetExtendedCodetext();

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

This sample shows how to use multi ECI mode in Extended Mode.

```csharp
[C#]
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");   

//generate codetext
string lCodetext = lTextBuilder.GetExtendedCodetext();

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.QrErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### See Also

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: Aspose::BarCode::Generation::QrExtCodetextBuilder class
linktitle: QrExtCodetextBuilder
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::Generation::QrExtCodetextBuilder class in C++.'
type: docs
weight: 3900
url: /cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Methods

| Method | Description |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Adds codetext with Extended Channel Identifier |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Adds FNC1 in first position to the extended codetext items |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Adds Group Separator (GS - '\u001D') to the extended codetext items |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Adds FNC1 in second position to the extended codetext items |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Adds plain codetext to the extended codetext items |
| virtual [Clear](../extcodetextbuilder/clear/)() | Clears extended codetext items |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Generates Extended codetext from the extended codetext list. |
## Remarks


Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of EncodeMode




Use TwoDDisplayText property of [BarcodeGenerator](../barcodegenerator/) to set visible text to removing managing characters.




This sample shows how to use FNC1 first position in Extended Mode. 
```cpp
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
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


This sample shows how to use FNC1 second position in Extended Mode. 
```cpp
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
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


This sample shows how to use multi ECI mode in Extended Mode. 
```cpp
[C#]
//create codetext
QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");   
<br>
//generate codetext
string lCodetext = lTextBuilder.GetExtendedCodetext();

//generate
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = lCodetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## See Also

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

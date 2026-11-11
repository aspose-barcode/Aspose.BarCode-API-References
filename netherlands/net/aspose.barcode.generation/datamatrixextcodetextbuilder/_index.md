---
title: "Klasse DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder klasse. Uitgebreide codetextgenerator voor 2D DataMatrix-streepjescodes voor de ExtendedCodetext-modus van EncodeMode"
type: docs
weight: 1210
url: /nl/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Uitgebreide codetekstgenerator voor 2D DataMatrix-barcodes voor ExtendedCodetext Mode van EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Voegt codetext toe met gedefinieerde encode-modus aan de uitgebreide codetextitems |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Voegt codetext toe met Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Voegt codetext toe met Extended Channel Identifier met gedefinieerde encode-modus |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Voegt platte codetext toe aan de uitgebreide codetextitems |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Leegt uitgebreide codetextitems |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Genereert Extended codetext uit de uitgebreide codetextlijst. |

## Voorbeelden

```csharp
[C#]
//Extended codetext-modus

//codetext maken
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();    

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Zie ook

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



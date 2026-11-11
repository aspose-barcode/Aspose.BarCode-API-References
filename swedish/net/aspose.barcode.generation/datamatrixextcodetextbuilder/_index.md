---
title: "Klass DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder-klass. Utökad kodtextgenerator för 2D DataMatrix-streckkoder för ExtendedCodetext-läge i EncodeMode"
type: docs
weight: 1210
url: /sv/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Utökad kodtextgenerator för 2D DataMatrix-streckkoder för ExtendedCodetext-läge i EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Lägger till kodtext med definierat kodningsläge till de utökade kodtextobjekten |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Lägger till kodtext med Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Lägger till kodtext med Extended Channel Identifier med definierat kodningsläge |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Rensar de utökade kodtextobjekten |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Genererar Extended kodtext från den utökade kodtextlistan. |

## Exempel

```csharp
[C#]
//Extended kodtextläge

//skapa kodtext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();    

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Se även

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



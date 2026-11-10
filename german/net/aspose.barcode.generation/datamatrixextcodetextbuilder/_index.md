---
title: "Klasse DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder Klasse. Erweiterter Codetext-Generator für 2D DataMatrix-Strichcodes für den ExtendedCodetext-Modus von EncodeMode"
type: docs
weight: 1210
url: /de/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Erweiterter Codetext-Generator für 2D DataMatrix-Barcodes für ExtendedCodetext Mode von EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Fügt Codetext mit definiertem Kodiermodus zu den erweiterten Codetext-Elementen hinzu |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Fügt Codetext mit Extended Channel Identifier hinzu |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Fügt Codetext mit Extended Channel Identifier und definiertem Kodiermodus hinzu |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste. |

## Beispiele

```csharp
[C#]
//Extended-Codetext-Modus

//Codetext erstellen
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();    

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Siehe auch

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



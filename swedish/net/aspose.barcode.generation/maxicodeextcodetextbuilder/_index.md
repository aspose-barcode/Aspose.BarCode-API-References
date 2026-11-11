---
title: "Klass MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder-klass. Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /sv/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Utökad kodtextgenerator för MaxiCode-streckkoder för ExtendedCodetext-läge i MaxiCodeEncodeMode

Använd egenskapen TwoDDisplayText i BarcodeGenerator för att ställa in synlig text genom att ta bort hanterande tecken.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Lägger till kodtext med Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Rensar de utökade kodtextobjekten |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Genererar Extended kodtext från den utökade kodtextlistan. |

## Exempel

Detta exempel visar hur man använder MaxiCodeExtCodetextBuilder i Extended-läge.

```csharp
[C#]
//skapa kodtext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();    

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Se även

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



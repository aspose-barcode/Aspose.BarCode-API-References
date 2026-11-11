---
title: "Klass AztecExtCodetextBuilder"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder-klass. Utökad kodtextgenerator för Aztec-streckkoder för ExtendedCodetext-läge i AztecEncodeMode"
type: docs
weight: 950
url: /sv/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Utökad kodtextgenerator för Aztec-streckkoder för ExtendedCodetext-läge i AztecEncodeMode

Använd egenskapen TwoDDisplayText i BarcodeGenerator för att ställa in synlig text genom att ta bort hanterande tecken.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Lägger till kodtext med Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Rensar de utökade kodtextobjekten |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Genererar Extended kodtext från den utökade kodtextlistan. |

## Exempel

Detta exempel visar hur man använder AztecExtCodetextBuilder i Extended-läge.

```csharp
[C#]
//skapa kodtext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//generera kodtext
string codetext = textBuilder.GetExtendedCodetext();    

//generera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Se även

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



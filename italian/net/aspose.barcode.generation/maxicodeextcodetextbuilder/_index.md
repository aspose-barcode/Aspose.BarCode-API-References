---
title: "Classe MaxiCodeExtCodetextBuilder"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder class. Generatore di codetext esteso per codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /it/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Generatore di codetext esteso per codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode

Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Il costruttore predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Aggiunge il codetext con Identificatore di Canale Esteso |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Aggiunge il codetext semplice agli elementi di codetext esteso |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Cancella gli elementi di codetext esteso |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Genera il codetext esteso dall'elenco di codetext esteso. |

## Esempi

Questo esempio mostra come utilizzare MaxiCodeExtCodetextBuilder in modalità Extended.

```csharp
[C#]
//crea codetext
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();    

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Vedi anche

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



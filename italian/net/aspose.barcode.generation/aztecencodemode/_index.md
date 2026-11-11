---
title: "Enum AztecEncodeMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Enum Aspose.BarCode.Generation.AztecEncodeMode. Modalità di codifica per i codici a barre Aztec"
type: docs
weight: 940
url: /it/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Modalità di codifica per i codici a barre Aztec.

```csharp
public enum AztecEncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. |
| Extended | `3` | Modalità estesa che supporta più modalità ECI. |
| Binary | `4` | In modalità Binaria, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione. |
| ECI | `5` | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (precedenti al 2006) potrebbero non supportare questa modalità. |

## Esempi

```csharp
[C#]
//Modalità Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Modalità Extended
//crea codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();    

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Vedi anche

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



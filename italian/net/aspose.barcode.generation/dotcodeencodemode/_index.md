---
title: "Enum DotCodeEncodeMode"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.Generation.DotCodeEncodeMode enum. Modalità di codifica per i codici a barre DotCode"
type: docs
weight: 1240
url: /it/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Modalità di codifica per i codici a barre DotCode.

```csharp
public enum DotCodeEncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | `0` | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. |
| Binary | `3` | In modalità Binaria, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione. |
| ECI | `4` | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (precedenti al 2006) potrebbero non supportare questa modalità. |
| Extended | `5` | Modalità estesa che supporta più modalità ECI. |

## Esempi

```csharp
[C#]
//Modalità automatica con macro
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Modalità Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Modalità Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Modalità codetext esteso
//crea codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();    

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Vedi anche

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Modalità di codifica del codificatore DataMatrix, predefinita su Auto in C++."
type: docs
weight: 6300
url: /it/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Modalità di codifica dell'encoder DataMatrix, predefinita su Auto

```cpp
enum class DataMatrixEncodeMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. |
| ASCII | 1 | Codifica un carattere alfanumerico o due caratteri numerici per byte. |
| C40 | 8 | Utilizza la codifica C40. Codifica alfanumerici maiuscoli, minuscoli e caratteri speciali. |
| Testo | 9 | Utilizza la codifica Text. Codifica alfanumerici minuscoli, maiuscoli e caratteri speciali. |
| EDIFACT | 10 | Utilizza la codifica EDIFACT. Usa sei bit per carattere, codifica cifre, lettere maiuscole e molti segni di punteggiatura, ma non supporta le lettere minuscole. |
| ANSIX12 | 11 | Utilizza la codifica ANSI X12. |
| Esteso | 13 |  |
| Base256 | 14 | Codifica valori a 8 bit. |
| Binario | 15 | In modalità Binario, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | 16 | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |

## Osservazioni


Questo esempio mostra come gestire il codetext in modalità Estesa.
```cpp
[C#]
//Modalità Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Modalità Byte
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Modalità codetext estesa
//crea codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//genera codetext
string codetext = textBuilder.GetExtendedCodetext();

//genera
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

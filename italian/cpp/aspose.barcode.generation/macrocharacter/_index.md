---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. I valori dei Macro Characters 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Il Macro character 05 è tradotto in \"[)>\\u001E05\\u001D\" come intestazione dei dati decodificati e \"\\u001E\\u0004\" come trailer dei dati decodificati. Il Macro character 06 è tradotto in \"[)>\\u001E06\\u001D\" come intestazione dei dati decodificati e \"\\u001E\\u0004\" come trailer dei dati decodificati in C++."
type: docs
weight: 7300
url: /it/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


I valori dei Macro Character 05 e 06 sono usati per ottenere una codifica più compatta in modalità speciali. Il Macro carattere 05 è tradotto in \"[)>\\u001E05\\u001D\" come intestazione dati decodificati e \"\\u001E\\u0004\" come trailer dati decodificati. Il Macro carattere 06 è tradotto in \"[)>\\u001E06\\u001D\" come intestazione dati decodificati e \"\\u001E\\u0004\" come trailer dati decodificati.

```cpp
enum class MacroCharacter
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Nessuno | 0 | Nessun Macro Character è aggiunto ai dati del codice a barre. |
| Macro05 | 5 | Il Macro character 05 è aggiunto ai dati del codice a barre nella prima posizione. Il carattere GS1 Data Identifier ISO 15434 è tradotto in "[)>\u001E05\u001D" come intestazione dei dati decodificati e "\u001E\u0004" come trailer dei dati decodificati. |
| Macro06 | 6 | Il Macro character 06 è aggiunto ai dati del codice a barre nella prima posizione. Il carattere ASC MH10 Data Identifier ISO 15434 è tradotto in "[)>\u001E06\u001D" come intestazione dei dati decodificati e "\u001E\u0004" come trailer dei dati decodificati. |

## Osservazioni


Questi esempi mostrano come codificare i Macro Characters in MicroPdf417 e DataMatrix
```cpp
[C#]
//Per generare un messaggio GS1 autoidentificato come questo "(10)123ABC(10)123ABC" nel formato ISO 15434 è necessario:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Codifica MicroPdf417 con Macro 05 la stringa: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Codifica MicroPdf417 con Macro 06 la stringa: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

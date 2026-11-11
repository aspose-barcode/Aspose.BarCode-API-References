---
title: "Classe GS1Codetext"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Aspose.BarCode.ComplexBarcode.GS1Codetext class. Rappresenta il codetext GS1 per la codifica e la decodifica come una sequenza ordinata di elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono preservati. La rappresentazione tra parentesi ha la forma AIvalueAIvalue. Una parentesi di apertura letterale  all'interno di un valore deve essere scritta come  (questa è l'unica sequenza di escape supportata). Una parentesi di chiusura  all'interno di un valore non richiede escape."
type: docs
weight: 530
url: /it/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Rappresenta il codetext GS1 per la codifica e la decodifica come una sequenza ordinata di elementi Application Identifier. L'ordine di origine e gli Application Identifier ripetuti sono preservati. La rappresentazione tra parentesi ha la forma (AI)value(AI)value. Una parentesi di apertura letterale '(' all'interno di un valore deve essere scritta come \\(; questa è l'unica sequenza di escape supportata. Una parentesi di chiusura ')' all'interno di un valore non richiede escape.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Ottiene o imposta il tipo di codice a barre utilizzato per codificare questo codetext GS1. I tipi supportati sono GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR e i tipi GS1 DataBar. Il valore predefinito è GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Restituisce il numero di elementi Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Restituisce una copia di tutti gli elementi nell'ordine di origine. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Restituisce un elemento in base alla sua posizione nella sequenza ordinata. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Analizza una stringa di elemento GS1 tra parentesi nella forma (AI)value(AI)value. Una parentesi '(' letterale all'interno di un valore deve essere scritta come \\(; nessun'altra sequenza di escape è supportata e ')' non richiede escape. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Aggiunge un elemento Application Identifier convalidato. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Restituisce tutti i valori di un Application Identifier nell'ordine di origine. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Ottiene il tipo di codice a barre utilizzato per codificare questo codetext GS1. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Costruisce il codetext GS1 tra parentesi nella forma (AI)value(AI)value. Le parentesi di apertura letterali nei valori sono escape come \\(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Restituisce il primo valore di un Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Inizializza questa istanza dal codetext GS1 tra parentesi nella forma (AI)value(AI)value. Gli elementi esistenti vengono sostituiti solo dopo che il codetext fornito è stato analizzato con successo. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Restituisce la rappresentazione GS1 tra parentesi nella forma (AI)value(AI)value. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)value(AI)value e restituisce errori di convalida strutturati. Una parentesi '(' letterale all'interno di un valore deve essere scritta come \\(; nessun'altra sequenza di escape è supportata e ')' non richiede escape. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Convalida una stringa di elemento GS1 tra parentesi nella forma (AI)value(AI)value senza creare un oggetto. Una parentesi '(' letterale all'interno di un valore deve essere scritta come \\(; nessun'altra sequenza di escape è supportata e ')' non richiede escape. |

### Vedi anche

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



---
title: "GS1Codetext.TryParse"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Metodo GS1Codetext. Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma AIvalueAIvalue e restituisce errori di convalida strutturati. Un letterale  all'interno di un valore deve essere scritto come  nessun'altra sequenza di escape è supportata e  non richiede escape."
type: docs
weight: 140
url: /it/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)value(AI)value e restituisce errori di convalida strutturati. Una parentesi '(' letterale all'interno di un valore deve essere scritta come \\(; nessun'altra sequenza di escape è supportata e ')' non richiede escape.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | String | Stringa di elemento GS1 tra parentesi da analizzare. |
| result | GS1Codetext& | Quando questo metodo restituisce true, contiene il codetext GS1 analizzato; altrimenti null. |
| validationResult | GS1ValidationResult& | Contiene il risultato della convalida, o null quando *value* è null. |

### Valore restituito

True quando l'analisi ha successo; altrimenti false.

### Vedi anche

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)



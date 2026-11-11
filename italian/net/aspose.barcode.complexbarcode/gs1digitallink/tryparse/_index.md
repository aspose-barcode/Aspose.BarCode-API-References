---
title: "GS1DigitalLink.TryParse"
second_title: "Riferimento API Aspose.BarCode per .NET"
description: "Metodo GS1DigitalLink. Tenta di analizzare un URI GS1 Digital Link non compresso e restituisce errori di convalida strutturati"
type: docs
weight: 190
url: /it/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Tenta di analizzare un URI GS1 Digital Link non compresso e restituisce errori di convalida strutturati.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | String | URI GS1 Digital Link da analizzare. |
| result | GS1DigitalLink& | Quando questo metodo restituisce true, contiene il GS1 Digital Link analizzato; altrimenti null. |
| validationResult | GS1ValidationResult& | Contiene il risultato della convalida, o null quando *value* è null. |

### Valore restituito

True quando l'analisi ha successo; altrimenti false.

### Vedi anche

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)



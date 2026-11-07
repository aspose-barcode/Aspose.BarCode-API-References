---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " method. Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)value(AI)value e restituisce errori di validazione strutturati. Un letterale ''('' all'interno di un valore deve essere scritto come (; nessun'altra sequenza di escape è supportata, e '')'' non richiede escape in C++."
type: docs
weight: 1600
url: /it/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Tenta di analizzare una stringa di elemento GS1 tra parentesi nella forma (AI)valore(AI)valore e restituisce errori di convalida strutturati. Un '(' letterale all'interno di un valore deve essere scritto come (; nessun'altra sequenza di escape è supportata, e ')' non richiede escape.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | System::String | Stringa dell'elemento GS1 tra parentesi da analizzare. |
| result | System::SharedPtr\<GS1Codetext\>\& | Quando questo metodo restituisce true, contiene il testo codificato GS1 analizzato; altrimenti null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contiene il risultato della validazione, o null quando *value* è null. |

### ReturnValue

True quando l'analisi ha successo; altrimenti false.

## Vedi anche

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

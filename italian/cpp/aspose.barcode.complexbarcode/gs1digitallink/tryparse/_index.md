---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Tenta di analizzare un URI GS1 Digital Link non compresso e restituisce errori di validazione strutturati in C++."
type: docs
weight: 2000
url: /it/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Tenta di analizzare un URI non compresso di GS1 Digital Link e restituisce errori di validazione strutturati.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | System::String | URI GS1 Digital Link da analizzare. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Quando questo metodo restituisce true, contiene il GS1 Digital Link analizzato; altrimenti null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contiene il risultato della validazione, o null quando *value* è null. |

### ReturnValue

True quando l'analisi ha successo; altrimenti false.

## Vedi anche

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " method. Probeert een tussen haakjes staande GS1-elementreeks te parseren in de vorm (AI)value(AI)value en retourneert gestructureerde validatiefouten. Een letterlijke ''('' binnen een waarde moet worden geschreven als (; er wordt geen andere escape‑reeks ondersteund, en '')'' hoeft niet te worden geescaped in C++."
type: docs
weight: 1600
url: /nl/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Probeert een tussen haakjes gegane GS1-elementreeks te parseren in de vorm (AI)waarde(AI)waarde en retourneert gestructureerde validatiefouten. Een letterlijk '(' binnen een waarde moet worden geschreven als (; er wordt geen andere escape‑reeks ondersteund, en ')' hoeft niet te worden geescaped.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | System::String | Tussen haakjes staande GS1-elementreeks om te parseren. |
| result | System::SharedPtr\<GS1Codetext\>\& | Wanneer deze methode true retourneert, bevat de geparseerde GS1-codetekst; anders null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Bevat het validatieresultaat, of null wanneer *value* null is. |

### ReturnValue

True wanneer het parseren slaagt; anders false.

## Zie ook

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

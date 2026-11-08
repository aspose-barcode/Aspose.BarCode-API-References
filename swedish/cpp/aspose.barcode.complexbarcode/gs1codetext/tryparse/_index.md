---
title: "metod"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Försöker tolka en hakparentes‑inramad GS1‑elementsträng i formatet (AI)värde(AI)värde och returnerar strukturerade valideringsfel. Ett bokstavligt ''('' inuti ett värde måste skrivas som (; ingen annan escape‑sekvens stöds, och '')'' kräver ingen escaping i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Försöker tolka en hakparentesomsluten GS1-elementsträng i formatet (AI)värde(AI)värde och returnerar strukturerade valideringsfel. Ett bokstavligt '(' inuti ett värde måste skrivas som (; ingen annan escape‑sekvens stöds, och ')' kräver ingen escaping.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::String | Hakparentes‑inramad GS1‑elementsträng att tolka. |
| resultat | System::SharedPtr\\<GS1Codetext\\>\\& | När den här metoden returnerar true, innehåller den den tolkade GS1‑kodtexten; annars null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Innehåller valideringsresultatet, eller null när *value* är null. |

### ReturnValue

Sant när parsning lyckas; annars falskt.

## Se även

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

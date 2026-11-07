---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu parsen und gibt strukturierte Validierungsfehler zurück. Ein wörtliches ''('' innerhalb eines Wertes muss als (; geschrieben werden; keine andere Escape-Sequenz wird unterstützt, und '')'' muss in C++ nicht escaped werden."
type: docs
weight: 1600
url: /de/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu analysieren und gibt strukturierte Validierungsfehler zurück. Ein wörtliches '(' innerhalb eines Wertes muss als ( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | System::String | Geklammerter GS1-Element-String zum Parsen. |
| Ergebnis | System::SharedPtr\<GS1Codetext\>\& | Wenn diese Methode true zurückgibt, enthält sie den geparsten GS1-Codetext; andernfalls null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Enthält das Validierungsergebnis, oder null, wenn *value* null ist. |

### ReturnValue

Wahr, wenn das Parsen erfolgreich ist; andernfalls falsch.

## Siehe auch

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

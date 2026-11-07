---
title: "Methode"
linktitle: "Validieren"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Validiert einen geklammerten GS1-Element-String in der Form (AI)value(AI)value ohne ein Objekt zu erstellen. Ein wörtliches ''('' innerhalb eines Wertes muss als ( geschrieben werden; keine andere Escape‑Sequenz wird unterstützt, und '')'' muss in C++ nicht escaped werden."
type: docs
weight: 1400
url: /de/cpp/aspose.barcode.complexbarcode/gs1codetext/validate/
---
## GS1Codetext::Validate method


Validiert einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert, ohne ein Objekt zu erstellen. Ein wörtliches '(' innerhalb eines Wertes muss als ( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden.

```cpp
static System::SharedPtr<Common::GS1ValidationResult> Aspose::BarCode::ComplexBarcode::GS1Codetext::Validate(System::String value)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | System::String | Geklammerten GS1-Element-String zum Validieren. |

### ReturnValue

Strukturiertes Validierungsergebnis.

## Siehe auch

* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

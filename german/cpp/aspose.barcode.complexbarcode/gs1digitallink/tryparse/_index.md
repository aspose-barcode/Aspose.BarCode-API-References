---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Versucht, eine unkomprimierte GS1 Digital Link URI zu parsen und gibt strukturierte Validierungsfehler in C++ zurück."
type: docs
weight: 2000
url: /de/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Versucht, eine unkomprimierte GS1 Digital Link-URI zu parsen und gibt strukturierte Validierungsfehler zurück.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | System::String | Zu parsende GS1 Digital Link URI. |
| Ergebnis | System::SharedPtr\<GS1DigitalLink\>\& | Wenn diese Methode true zurückgibt, enthält sie den geparsten GS1 Digital Link; andernfalls null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Enthält das Validierungsergebnis, oder null, wenn *value* null ist. |

### ReturnValue

Wahr, wenn das Parsen erfolgreich ist; andernfalls falsch.

## Siehe auch

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

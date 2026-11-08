---
title: "metod"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Försöker parsa en okomprimerad GS1 Digital Link-URI och returnerar strukturerade valideringsfel i C++."
type: docs
weight: 2000
url: /sv/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Försöker att parsa en okomprimerad GS1 Digital Link‑URI och returnerar strukturerade valideringsfel.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | System::String | GS1 Digital Link-URI att parsa. |
| resultat | System::SharedPtr\<GS1DigitalLink\>\& | När denna metod returnerar true innehåller den den parsade GS1 Digital Link; annars null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Innehåller valideringsresultatet, eller null när *value* är null. |

### ReturnValue

Sant när parsning lyckas; annars falskt.

## Se även

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Probeert een ongecomprimeerde GS1 Digital Link URI te parseren en retourneert gestructureerde validatiefouten in C++."
type: docs
weight: 2000
url: /nl/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Probeert een ongecomprimeerde GS1 Digital Link-URI te parseren en retourneert gestructureerde validatiefouten.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | System::String | GS1 Digital Link URI om te parseren. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Wanneer deze methode true retourneert, bevat deze de geparseerde GS1 Digital Link; anders null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Bevat het validatieresultaat, of null wanneer *value* null is. |

### ReturnValue

True wanneer het parseren slaagt; anders false.

## Zie ook

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

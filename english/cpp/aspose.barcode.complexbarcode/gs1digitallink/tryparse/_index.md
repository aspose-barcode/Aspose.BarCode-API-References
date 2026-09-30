---
title:  method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors in C++.'
type: docs
weight: 2000
url: /cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Attempts to parse an uncompressed GS1 Digital Link URI and returns structured validation errors.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Description |
| --- | --- | --- |
| value | System::String | GS1 Digital Link URI to parse. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | When this method returns true, contains the parsed GS1 Digital Link; otherwise null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contains the validation result, or null when *value*  is null. |

### ReturnValue

True when parsing succeeds; otherwise false.

## See Also

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

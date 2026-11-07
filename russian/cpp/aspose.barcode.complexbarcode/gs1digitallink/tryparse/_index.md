---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Пытается разобрать несжатый URI GS1 Digital Link и возвращает структурированные ошибки проверки в C++."
type: docs
weight: 2000
url: /ru/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Пытается разобрать несжатый URI GS1 Digital Link и возвращает структурированные ошибки валидации.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| value | System::String | URI GS1 Digital Link для разбора. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Когда этот метод возвращает true, содержит разобранный GS1 Digital Link; иначе null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Содержит результат проверки, или null, когда *value*  равно null. |

### ReturnValue

True, когда разбор успешен; иначе false.

## См. также

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metodu. Sıkıştırılmamış bir GS1 Digital Link URI'sını ayrıştırmayı dener ve C++'ta yapılandırılmış doğrulama hatalarını döndürür."
type: docs
weight: 2000
url: /tr/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Sıkıştırılmamış bir GS1 Dijital Bağlantı URI'sini ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | System::String | Ayrıştırılacak GS1 Digital Link URI. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Bu metod true döndürdüğünde, ayrıştırılmış GS1 Digital Link'i içerir; aksi takdirde null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Doğrulama sonucunu içerir, ya da *value* null olduğunda null. |

### ReturnValue

Ayrıştırma başarılı olduğunda true; aksi takdirde false.

## Ayrıca Bakınız

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

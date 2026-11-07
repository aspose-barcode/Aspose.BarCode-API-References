---
title: "metode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. Mencoba mengurai URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur dalam C++."
type: docs
weight: 2000
url: /id/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Mencoba mengurai URI GS1 Digital Link yang tidak terkompresi dan mengembalikan kesalahan validasi terstruktur.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | System::String | URI GS1 Digital Link untuk diurai. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Ketika metode ini mengembalikan true, berisi GS1 Digital Link yang telah diurai; jika tidak, null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Berisi hasil validasi, atau null ketika *value*  null. |

### ReturnValue

True ketika parsing berhasil; jika tidak, false.

## Lihat Juga

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

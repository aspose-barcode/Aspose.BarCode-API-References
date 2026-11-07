---
title: "metode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mencoba memparse string elemen GS1 dalam kurung dengan format (AI)value(AI)value dan mengembalikan kesalahan validasi terstruktur. Literal ''('' di dalam nilai harus ditulis sebagai (; tidak ada urutan escape lain yang didukung, dan '')'' tidak memerlukan escaping di C++."
type: docs
weight: 1600
url: /id/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Mencoba mengurai string elemen GS1 dalam kurung dalam bentuk (AI)nilai(AI)nilai dan mengembalikan kesalahan validasi terstruktur. Tanda '(' literal di dalam nilai harus ditulis sebagai (; tidak ada urutan pelolosan lain yang didukung, dan ')' tidak memerlukan pelolosan.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | System::String | String elemen GS1 dalam kurung untuk diparse. |
| result | System::SharedPtr\<GS1Codetext\>\& | Ketika metode ini mengembalikan true, berisi kode teks GS1 yang diparse; jika tidak, null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Berisi hasil validasi, atau null ketika *value*  null. |

### ReturnValue

True ketika parsing berhasil; jika tidak, false.

## Lihat Juga

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Parantezli bir GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırmayı dener ve yapılandırılmış doğrulama hataları döndürür. Bir değerdeki gerçek ''('' karakteri (; olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve '')'' C++'ta kaçış gerektirmez."
type: docs
weight: 1600
url: /tr/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Parantezli bir GS1 öğe dizesini (AI)değer(AI)değer biçiminde ayrıştırmayı dener ve yapılandırılmış doğrulama hatalarını döndürür. Bir değerin içinde görülen '(' karakteri (; olarak yazılmalıdır; başka bir kaçış dizisi desteklenmez ve ')' kaçış gerektirmez.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | System::String | Parantezli GS1 öğe dizesi, ayrıştırılacak. |
| result | System::SharedPtr\<GS1Codetext\>\& | Bu yöntem true döndürdüğünde, ayrıştırılmış GS1 kod metnini içerir; aksi takdirde null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Doğrulama sonucunu içerir, ya da *value* null olduğunda null. |

### ReturnValue

Ayrıştırma başarılı olduğunda true; aksi takdirde false.

## Ayrıca Bakınız

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

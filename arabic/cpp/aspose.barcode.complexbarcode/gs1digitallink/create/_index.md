---
title: "طريقة"
linktitle: "إنشاء"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " الطريقة. ينشئ رابط GS1 الرقمي عن طريق نسخ جميع العناصر من نص شفرة GS1 واختيار المفتاح الأساسي المتاح الوحيد في C++."
type: docs
weight: 2100
url: /ar/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واختيار المفتاح الأساسي المتاح الوحيد.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| uriStem | System::String | بادئة URI مطلقة HTTP أو HTTPS قبل المفتاح الأساسي. |
| codetext | System::SharedPtr\<GS1Codetext\> | نص شفرة GS1 الذي تُنسخ عناصره. |

### ReturnValue

رابط GS1 Digital Link يحتوي على العناصر المنسوخة.

## انظر أيضًا

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


ينشئ GS1 Digital Link بنسخ جميع العناصر من نص رمز GS1 واستخدام المفتاح الأساسي المحدد.

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| uriStem | System::String | بادئة URI مطلقة HTTP أو HTTPS قبل المفتاح الأساسي. |
| codetext | System::SharedPtr\<GS1Codetext\> | نص شفرة GS1 الذي تُنسخ عناصره. |
| primaryApplicationIdentifier | System::String | المفتاح الأساسي AI. |

### ReturnValue

رابط GS1 Digital Link يحتوي على العناصر المنسوخة.

## انظر أيضًا

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

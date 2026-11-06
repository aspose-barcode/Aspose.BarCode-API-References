---
title: "فئة Aspose::BarCode::Generation::AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::AztecParameters. معلمات Aztec في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


معلمات Aztec.

```cpp
class AztecParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [get_ECIEncoding](./get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | مستوى تصحيح الأخطاء لأنواع الباركود Aztec. يجب أن تكون القيمة بين 5 إلى 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [get_LayersCount](./get_layerscount/)() const | يحصل على عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المدمج ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | معرّف الباركود لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون معرف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | عدد الباركودات لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | معرّف الملف لوضع الإلحاق المُنظم لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة |
| [get_SymbolMode](./get_symbolmode/)() const | يحصل على وضع رمز Aztec. القيمة الافتراضية: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | مستوى تصحيح الأخطاء لأنواع الباركود Aztec. يجب أن تكون القيمة بين 5 إلى 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [set_LayersCount](./set_layerscount/)(int32_t) | يضبط عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المدمج ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | معرّف الباركود لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون معرف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | عدد الباركودات لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | معرّف الملف لوضع الإلحاق المُنظم لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | يضبط وضع رمز Aztec. القيمة الافتراضية: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | يعيد تمثيل نصي قابل للقراءة للإنسان لهذا [AztecParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

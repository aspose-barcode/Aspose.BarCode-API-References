---
title: "فئة Aspose::BarCode::Generation::DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::DotCodeParameters. معلمات DotCode في C++."
type: docs
weight: 2200
url: /ar/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


معلمات DotCode.

```cpp
class DotCodeParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [get_Columns](./get_columns/)() const | يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode على الوضع التلقائي Auto. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يشير إلى ما إذا كان الرمز يُستخدم لإرشاد القارئ لتفسير البيانات التالية كتعليمات لتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [get_Rows](./get_rows/)() const | يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | يحدد معرف باركود وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | يحدد عدد باركودات وضع الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |
| [set_AspectRatio](./set_aspectratio/)(float) | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [set_Columns](./set_columns/)(int32_t) | يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode على الوضع التلقائي Auto. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | يشير إلى ما إذا كان الرمز يُستخدم لإرشاد القارئ لتفسير البيانات التالية كتعليمات لتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [set_Rows](./set_rows/)(int32_t) | يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | يحدد معرف باركود وضع الإلحاق المهيكل DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | يحدد عدد باركودات وضع الإلحاق المهيكل DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |
| [ToString](./tostring/)() const override | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [DotCodeParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

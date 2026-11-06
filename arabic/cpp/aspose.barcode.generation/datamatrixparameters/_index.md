---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::DataMatrixParameters class. معلمات DataMatrix في C++."
type: docs
weight: 2000
url: /ar/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


معلمات DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [get_EccType](./get_ecctype/)() const | يحصل على نوع ECC لـ Datamatrix. القيمة الافتراضية: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون EncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | قِيَم الأحرف الماكرو 05 و06 تُستخدم للحصول على ترميز أكثر تكثيفًا في أوضاع خاصة. يمكن استخدامها فقط مع [DataMatrixEccType.Ecc200](../datamatrixecctype/) أو [DataMatrixEccType.EccAuto](../datamatrixecctype/). لا يمكن استخدامها مع [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) القيمة الافتراضية: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | معرّف الباركود لوضع الإلحاق المهيكل لباركود Datamatrix. القيمة الافتراضية: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | عدد الباركودات لوضع الإلحاق المهيكل لباركود Datamatrix. القيمة الافتراضية: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | معرّف الملف لوضع الإلحاق المُنظم لباركود Datamatrix. القيمة الافتراضية: 0 |
| [get_Version](./get_version/)() const | يحصل على حجم رمز Datamatrix. القيمة الافتراضية: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | نسبة الارتفاع إلى العرض لوحدة [BarCode](../../aspose.barcode/) ثنائية الأبعاد. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | يضبط نوع ECC لDatamatrix. القيمة الافتراضية: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون EncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. القيمة الافتراضية: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | قِيَم الأحرف الماكرو 05 و06 تُستخدم للحصول على ترميز أكثر تكثيفًا في أوضاع خاصة. يمكن استخدامها فقط مع [DataMatrixEccType.Ecc200](../datamatrixecctype/) أو [DataMatrixEccType.EccAuto](../datamatrixecctype/). لا يمكن استخدامها مع [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) القيمة الافتراضية: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | معرّف الباركود لوضع الإلحاق المهيكل لباركود Datamatrix. القيمة الافتراضية: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | عدد الباركودات لوضع الإلحاق المهيكل لباركود Datamatrix. القيمة الافتراضية: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | معرّف الملف لوضع الإلحاق المُنظم لباركود Datamatrix. القيمة الافتراضية: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | يضبط حجم رمز Datamatrix. القيمة الافتراضية: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | يرجع تمثيلًا نصيًا قابلاً للقراءة لهذا [DataMatrixParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "فئة Aspose::BarCode::Generation::Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::Unit. تحدد قيمة الحجم بوحدات مختلفة (Pixel, Inches, إلخ) في C++."
type: docs
weight: 5000
url: /ar/cpp/aspose.barcode.generation/unit/
---
## Unit class


يحدد قيمة الحجم بوحدات مختلفة (Pixel، Inches، إلخ).

```cpp
class Unit : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يحدد ما إذا كانت هذه الحالة وكائن محدد، والذي يجب أن يكون أيضًا كائنًا من نوع [Unit](./)، لهما نفس القيمة. |
| [get_Document](./get_document/)() | يحصل على قيمة الحجم بوحدات المستند. |
| [get_Inches](./get_inches/)() | يحصل على قيمة الحجم بالبوصات. |
| [get_Millimeters](./get_millimeters/)() | يحصل على قيمة الحجم بالمليمترات. |
| [get_Pixels](./get_pixels/)() | يحصل على قيمة الحجم بالبكسلات. |
| [get_Point](./get_point/)() | يحصل على قيمة الحجم بالنقطة. |
| [get_Resolution](./get_resolution/)() const | Resolution |
| [GetHashCode](./gethashcode/)() const override | إرجاع رمز التجزئة لهذا الكائن. |
| [set_Document](./set_document/)(float) | يضبط قيمة الحجم بوحدات المستند. |
| [set_Inches](./set_inches/)(float) | يضبط قيمة الحجم بالبوصات. |
| [set_Millimeters](./set_millimeters/)(float) | يضبط قيمة الحجم بالمليمترات. |
| [set_Pixels](./set_pixels/)(float) | يضبط قيمة الحجم بالبكسلات. |
| [set_Point](./set_point/)(float) | يضبط قيمة الحجم بالنقطة. |
| [ToString](./tostring/)() const override | إرجاع تمثيل نصي قابل للقراءة للإنسان لهذا [Unit](./). |
## ملاحظات


يعرض هذا المثال كيفية إنشاء وحفظ صورة [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

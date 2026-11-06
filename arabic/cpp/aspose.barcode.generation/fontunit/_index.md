---
title: "Aspose::BarCode::Generation::FontUnit فئة"
linktitle: "FontUnit"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::FontUnit فئة. يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط حيث يكون الحجم في خاصية قيمة الوحدة Unit في C++."
type: docs
weight: 2500
url: /ar/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط حيث يكون الحجم في خاصية قيمة [Unit](../unit/).

```cpp
class FontUnit : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | يحصل على اسم الوجه لهذا الخط. |
| [get_Size](./get_size/)() const | يحصل على حجم هذا [FontUnit](./) بوحدة [Unit](../unit/) |
| [get_Style](./get_style/)() const | يحصل على معلومات النمط لهذا [FontUnit](./). |
| [set_FamilyName](./set_familyname/)(System::String) | يضبط اسم الوجه لهذا Font. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | يضبط معلومات النمط لهذا [FontUnit](./). |
## ملاحظات


يعرض هذا المثال كيفية إنشاء وحفظ صورة [BarCode](../../aspose.barcode/).
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

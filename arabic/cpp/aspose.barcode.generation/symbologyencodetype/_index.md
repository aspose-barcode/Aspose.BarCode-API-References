---
title: "فئة Aspose::BarCode::Generation::SymbologyEncodeType"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::SymbologyEncodeType. نوع ترميز الرموز. راجع EncodeTypes للحصول على نسخة في C++."
type: docs
weight: 4900
url: /ar/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


نوع ترميز الرموز. راجع [EncodeTypes](../encodetypes/) للحصول على نسخة.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseEncodeType](../baseencodetype/) المحددة. |
| [get_Classification](../baseencodetype/get_classification/)() const | يحصل على تصنيف هذا الترميز. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | يحصل على فهرس نوع الترميز |
| [get_TypeName](../baseencodetype/get_typename/)() const | يحصل على اسم نوع الترميز |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetString](../baseencodetype/getstring/)() | يقوم بتحويل كائن [BaseEncodeType](../baseencodetype/) إلى تمثيله النصي المكافئ. تنسيق السلسلة هو: \"Index:0; Name:Codabar\". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | يقوم بتحويل كائن [BaseEncodeType](../baseencodetype/) إلى تمثيله النصي المكافئ. تنسيق السلسلة هو: \"Index:-1; Name:None\". |
| static [Parse](../baseencodetype/parse/)(System::String) | يقوم بتحويل التمثيل النصي لاسم [BaseEncodeType](../baseencodetype/) إلى كائنه. |
| [ToString](../baseencodetype/tostring/)() const override | يعيد اسم [BaseEncodeType](../baseencodetype/) المعطى كسلسلة. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | يقوم بتحويل التمثيل النصي لـ [BaseEncodeType](../baseencodetype/) إلى كائنه. تشير قيمة الإرجاع إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | يقوم بتحويل التمثيل النصي لـ [BaseEncodeType](../baseencodetype/) إلى كائنه. تشير قيمة الإرجاع إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
## ملاحظات


يعرض هذا المثال كيفية الحصول على نسخة من الفئة [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## انظر أيضًا

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "فئة Aspose::BarCode::BarCodeRecognition::SingleDecodeType"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::SingleDecodeType. نوع فك تشفير واحد. راجع نوع فك التشفير للحصول على المثيل في C++."
type: docs
weight: 3200
url: /ar/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


نوع فك الترميز الفردي. راجع نوع فك الترميز للحصول على نسخة.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مدرجًا في القائمة المحددة. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [SingleDecodeType](./) المحددة. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | يعيد قيمة تشير إلى ما إذا كانت مجموعة [MultiDecodeType](../multidecodetype/) المحددة تحتوي فقط على هذا النوع من فك التشفير. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [SingleDecodeType](./) المحددة. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [BaseDecodeType](../basedecodetype/) المحددة. |
| [get_TypeIndex](./get_typeindex/)() const | يحصل على فهرس نوع فك التشفير |
| [get_TypeName](./get_typename/)() const | يحصل على اسم نوع فك التشفير |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetString](./getstring/)() | يحوّل كائن [SingleDecodeType](./) إلى تمثيله النصي المكافئ. تنسيق السلسلة هو: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | يحوّل كائن [SingleDecodeType](./) إلى تمثيله النصي المكافئ. تنسيق السلسلة هو: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | يحوّل التمثيل النصي لاسم [SingleDecodeType](./) إلى كائنه. |
| [ToString](./tostring/)() const override | يعيد اسم [SingleDecodeType](./) المعطى كسلسلة. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | يحوّل التمثيل النصي لـ [SingleDecodeType](./) إلى كائنه. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | يحوّل التمثيل النصي لـ [MultiDecodeType](../multidecodetype/) إلى كائنه. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | يحوّل التمثيل النصي لـ [BaseDecodeType](../basedecodetype/) إلى كائنه، بعد تحديد النوع الفعلي. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
## ملاحظات


يعرض هذا المثال كيفية الحصول على كائن من نوع فك تشفير واحد.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## انظر أيضًا

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

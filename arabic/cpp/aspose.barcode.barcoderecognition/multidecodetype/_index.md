---
title: "فئة Aspose::BarCode::BarCodeRecognition::MultiDecodeType"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::MultiDecodeType. نوع فك تشفير مركب في C++."
type: docs
weight: 2600
url: /ar/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


نوع فك الترميز المركب.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | يضيف نوعاً آخر من [SingleDecodeType](../singledecodetype/) إلى [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | تحقق مما إذا كان يحتوي هذا على جميع الأنواع من أنواع الباركود. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | هل يحتوي على أي من الأنواع |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة [MultiDecodeType](./) المحددة. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | يرجع قيمة تشير إلى ما إذا كانت مجموعة أنواع فك التشفير هذه تحتوي فقط على قيمة [SingleDecodeType](../singledecodetype/) المحددة. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يرجع قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة [MultiDecodeType](./) المحددة. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [BaseDecodeType](../basedecodetype/) المحددة. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | يستثني [SingleDecodeType](../singledecodetype/) من [MultiDecodeType](./) ويعيد مثيلاً جديداً من [MultiDecodeType](./). |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | يرجع عدد الأنواع الفردية. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetSingleTypes](./getsingletypes/)() | يمثل قائمة بالأنواع الفردية. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | ينشئ مثيلاً جديداً من الفئة [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | ينشئ مثيلاً جديداً من الفئة [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | طريقة مُعاد تعريفها تمثل [MultiDecodeType](./) كسلسلة نصية. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | يحوّل تمثيل السلسلة النصية لـ [MultiDecodeType](./) إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | يحوِّل تمثيل النص لـ [SingleDecodeType](../singledecodetype/) إلى مثيلها. تشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل نجحت أم فشلت. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | يحوّل التمثيل النصي لـ [BaseDecodeType](../basedecodetype/) إلى كائنه، بعد تحديد النوع الفعلي. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
## ملاحظات


يوضح هذا المثال كيفية إنشاء أنواع MultiDecode مركبة تجمع بين [SingleDecodeType](../singledecodetype/) وأنواع MultiDecode.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## انظر أيضًا

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

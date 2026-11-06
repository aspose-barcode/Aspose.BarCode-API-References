---
title: "فئة Aspose::BarCode::BarCodeRecognition::BaseDecodeType"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::BaseDecodeType. الفئة الأساسية لـ MultiDecodeType و SingleDecodeType في C++."
type: docs
weight: 900
url: /ar/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


الفئة الأساسية لـ [MultiDecodeType](../multidecodetype/) و [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | يحدد ما إذا كان أي من أنواع فك التشفير المعطاة مدرجًا في |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [SingleDecodeType](../singledecodetype/) المحددة. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن يساوي قيمة [MultiDecodeType](../multidecodetype/) المحددة. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](./) المحددة. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | يحوِّل تمثيل النص لـ [SingleDecodeType](../singledecodetype/) إلى مثيلها. تشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل نجحت أم فشلت. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | يحوّل التمثيل النصي لـ [MultiDecodeType](../multidecodetype/) إلى كائنه. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | يحوِّل تمثيل النص لـ [BaseDecodeType](./) إلى مثيلها بعد تحديد النوع الفعلي. تشير قيمة الإرجاع إلى ما إذا كانت عملية التحويل نجحت أم فشلت. |
## ملاحظات


يعرض هذا المثال كيفية استخدام [BaseDecodeType](./) مع [SingleDecodeType](../singledecodetype/) و [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

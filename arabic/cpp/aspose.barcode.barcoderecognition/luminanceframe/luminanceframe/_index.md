---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " مُنشئ. يهيئ مثيلاً جديداً من الفئة LuminanceFrame بدون حشو بين الصفوف. المسافة بين الصفوف المتجاورة تساوي العرض في C++."
type: docs
weight: 600
url: /ar/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


يهيئ مثيلاً جديداً من الفئة [LuminanceFrame](../) بدون حشو بين الصفوف. المسافة بين الصفوف المتجاورة تساوي *العرض* .

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | بيانات الإضاءة التي تحتوي على بايت واحد لكل بكسل. |
| العرض | int32_t | عرض الإطار بالبكسل. |
| الارتفاع | int32_t | ارتفاع الإطار بالبكسل. |
| rotationDegrees | int32_t | الدوران باتجاه عقارب الساعة المطلوب لعرض الإطار بشكل عمودي. القيم المدعومة هي 0، 90، 180 و270. القيمة الافتراضية هي 0. |

## انظر أيضًا

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


يهيئ مثيلاً جديداً من الفئة [LuminanceFrame](../) مع خطوة الصف المحددة.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | بيانات الإضاءة التي تحتوي على بايت واحد لكل بكسل. |
| العرض | int32_t | عرض الإطار بالبكسل. |
| الارتفاع | int32_t | ارتفاع الإطار بالبكسل. |
| rowStride | int32_t | المسافة بالبايت بين بدايات صفين متجاورين. لا يمكن أن تكون القيمة أقل من *width* . |
| rotationDegrees | int32_t | الدوران باتجاه عقارب الساعة المطلوب لعرض الإطار بشكل عمودي. القيم المدعومة هي 0، 90، 180 و 270. |

## انظر أيضًا

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

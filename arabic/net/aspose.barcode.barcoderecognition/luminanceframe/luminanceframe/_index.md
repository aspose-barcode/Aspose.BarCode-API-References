---
title: "LuminanceFrame.LuminanceFrame"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "منشئ LuminanceFrame. يهيئ مثلاً جديدًا من فئة LuminanceFrame دون حشو بين الصفوف. المسافة بين الصفوف المتجاورة تساوي العرض"
type: docs
weight: 10
url: /ar/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

يُهيئ مثلاً جديدًا من الفئة [`LuminanceFrame`](../) دون حشو بين الصفوف. المسافة بين الصفوف المتجاورة تساوي *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | Byte[] | بيانات الإضاءة التي تحتوي على بايت واحد لكل بكسل. |
| width | Int32 | عرض الإطار بالبكسل. |
| height | Int32 | ارتفاع الإطار بالبكسل. |
| rotationDegrees | Int32 | الدوران باتجاه عقارب الساعة المطلوب لعرض الإطار بشكل عمودي. القيم المدعومة هي 0 و 90 و 180 و 270. القيمة الافتراضية هي 0. |

### انظر أيضًا

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

يُنشئ مثيلاً جديدًا من الفئة [`LuminanceFrame`](../) مع خطوة الصف المحددة.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | Byte[] | بيانات الإضاءة التي تحتوي على بايت واحد لكل بكسل. |
| width | Int32 | عرض الإطار بالبكسل. |
| height | Int32 | ارتفاع الإطار بالبكسل. |
| rowStride | Int32 | المسافة بالبايت بين بدايات صفين متجاورين. لا يمكن أن تكون القيمة أقل من *width*. |
| rotationDegrees | Int32 | الدوران باتجاه عقارب الساعة المطلوب لعرض الإطار بشكل عمودي. القيم المدعومة هي 0 و 90 و 180 و 270. |

### انظر أيضًا

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



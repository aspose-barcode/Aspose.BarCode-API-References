---
title: "enum"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 3700
url: /ar/cpp/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enum




```cpp
enum class ComplexBackgroundMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | في الوقت الحالي هو نفسه Disabled. يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| معطل | 1 | يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| مفعل | 2 | يفعل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |

## ملاحظات


الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات الملونة في الصور الملونة.

هذا المثال يوضح كيفية استخدام وضع ComplexBackground
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

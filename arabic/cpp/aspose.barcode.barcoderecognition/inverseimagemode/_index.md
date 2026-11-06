---
title: "enum"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 3900
url: /ar/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | 0 | يعطل التعرف الإضافي على الباركودات في الصور العكسية لجميع أنواع الباركود باستثناء رمز [QR](../../aspose.barcode.barcoderecognition.qr/). |
| معطل | 1 | يعطل التعرف الإضافي على الباركودات في الصور العكسية. |
| مفعل | 2 | يفعل التعرف الإضافي على الباركودات في الصور العكسية |

## ملاحظات


الوضع الذي يفعّل أو يوقف التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (السطوع).

يعرض هذا المثال كيفية استخدام وضع InverseImage
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

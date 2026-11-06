---
title: "enum"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 3600
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enum




```cpp
enum class BarcodeQualityMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| عالي | 0 | يفعل أساليب التعرف لباركودات عالية الجودة. |
| عادي | 1 | يفعل أساليب التعرف لباركودات جودة شائعة (عادية). |
| منخفض | 2 | يفعل أساليب التعرف لباركودات منخفضة الجودة. |

## ملاحظات


الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المحددة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

يعرض هذا المثال كيفية استخدام وضع BarcodeQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

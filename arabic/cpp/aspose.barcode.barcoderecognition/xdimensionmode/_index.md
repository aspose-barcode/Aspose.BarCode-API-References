---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 4000
url: /ar/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| تلقائي | 0 | قيمة XDimension يتم اكتشافها بواسطة الذكاء الاصطناعي (SVM). في الوقت الحالي هي نفسها كـ Normal |
| صغير | 1 | يكشف عن الباركودات ذات XDimension صغير في 1 بكسل أو أكثر بجودة من BarcodeQuality |
| عادي | 2 | يكشف عن الباركودات ذات XDimension كلاسيكي في 2 بكسل أو أكثر بجودة من BarcodeQuality أو باركودات عالية الجودة. |
| كبير | 3 | يكشف عن الباركودات ذات XDimension كبير بجودة من BarcodeQuality تم التقاطها بكاميرات عالية الدقة. |
| UseMinimalXDimension | 4 | يكشف عن الرموز الشريطية من الحجم المحدد في MinimalXDimension مع الجودة من BarcodeQuality |

## ملاحظات


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

يعرض هذا المثال كيفية استخدام وضع XDimension
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

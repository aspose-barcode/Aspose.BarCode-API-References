---
title: "enum"
linktitle: "DeconvolutionMode"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "كيفية استخدام enum في C++."
type: docs
weight: 3800
url: /ar/cpp/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enum




```cpp
enum class DeconvolutionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| سريع | 0 | يفعل طرق فك الالتفاف السريعة للصور عالية الجودة. |
| عادي | 1 | يفعل طرق فك الالتفاف العادية للصور الشائعة. |
| بطيء | 2 | يفعل طرق فك الالتفاف البطيئة للصور منخفضة الجودة. |

## ملاحظات


وضع فك الالتفاف (استعادة الصورة) الذي يحدد مستوى تدهور الصورة. في الأصل، فك الالتفاف هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بواسطة أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. نظرًا لعدم قدرتنا على اكتشاف الدالة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي.

يعرض هذا المثال كيفية استخدام وضع Deconvolution
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## انظر أيضًا

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

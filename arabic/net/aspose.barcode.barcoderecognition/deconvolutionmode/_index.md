---
title: "تعداد DeconvolutionMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.DeconvolutionMode تعداد. وضع استعادة الصور بالتحليل العكسي الذي يحدد مستوى تدهور الصورة. في الأصل، التحليل العكسي هو دالة يمكنها استعادة الصورة المتدهورة والمتشابكة بسبب أي دالة طبيعية مثل الضبابية أثناء الحصول على الصورة بالكاميرا. لأنه لا يمكننا اكتشاف الدالة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي"
type: docs
weight: 240
url: /ar/net/aspose.barcode.barcoderecognition/deconvolutionmode/
---
## DeconvolutionMode enumeration

وضع التحليل العكسي (استعادة الصور) الذي يحدد مستوى تدهور الصورة. في الأصل، التحليل العكسي هو دالة يمكنها استعادة الصورة المتدهورة (المتشابكة) بسبب أي دالة طبيعية مثل الضبابية، أثناء الحصول على الصورة بالكاميرا. لأنه لا يمكننا اكتشاف الدالة التي تفسد الصورة، علينا فحص أكثر الدوال المعروفة مثل الحدة أو التشكل الرياضي.

```csharp
public enum DeconvolutionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Fast | `0` | يتيح طرق التحليل العكسي السريعة للصور عالية الجودة. |
| Normal | `1` | يتيح طرق التحليل العكسي العادية للصور الشائعة. |
| Slow | `2` | يتيح طرق التحليل العكسي البطيئة للصور منخفضة الجودة. |

## أمثلة

يعرض هذا المثال كيفية استخدام وضع Deconvolution

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.Deconvolution = DeconvolutionMode.Slow;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: "التعداد XDimensionMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "التعداد Aspose.BarCode.BarCodeRecognition.XDimensionMode. وضع التعرف الذي يحدد الحجم من 1 إلى ما لا نهاية للعنصر الأدنى للباركود: خلية مصفوفة أو شريط"
type: docs
weight: 400
url: /ar/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

وضع التعرف الذي يحدد حجم العنصر الأدنى للباركود (من 1 إلى ما لا نهاية): خلية مصفوفة أو شريط.

```csharp
public enum XDimensionMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | قيمة XDimension يتم اكتشافها بواسطة الذكاء الاصطناعي (SVM). في الوقت الحالي هي نفسها كالوضع العادي |
| Small | `1` | يكشف عن الباركودات ذات XDimension صغير في بكسل واحد أو أكثر بجودة من BarcodeQuality |
| Normal | `2` | يكشف عن الباركودات ذات XDimension كلاسيكي في بكسلين أو أكثر بجودة من BarcodeQuality أو باركودات عالية الجودة. |
| Large | `3` | يكشف عن الباركودات ذات XDimension كبير بجودة من BarcodeQuality تم التقاطها بكاميرات عالية الدقة. |
| UseMinimalXDimension | `4` | يكشف عن الباركودات بناءً على الحجم المحدد في MinimalXDimension بجودة من BarcodeQuality |

## أمثلة

يعرض هذا المثال كيفية استخدام وضع XDimension

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: "تعداد BarcodeQualityMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "تعداد Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode. الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف."
type: docs
weight: 110
url: /ar/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

الوضع الذي يتيح للطرق التعرف على عناصر الباركود بالجودة المختارة. عنصر الباركود ذو الجودة الأقل يتطلب طرقًا أكثر صعوبة مما يبطئ عملية التعرف.

```csharp
public enum BarcodeQualityMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| High | `0` | يتيح طرق التعرف على الباركودات ذات الجودة العالية. |
| Normal | `1` | يتيح طرق التعرف على الباركودات ذات الجودة العادية (المشتركة). |
| Low | `2` | يتيح طرق التعرف على الباركودات ذات الجودة المنخفضة. |

## أمثلة

يعرض هذا المثال كيفية استخدام وضع BarcodeQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



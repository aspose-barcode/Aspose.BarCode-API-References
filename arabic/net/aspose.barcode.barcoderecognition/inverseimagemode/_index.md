---
title: "تعداد InverseImageMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode تعداد. الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة السطوع"
type: docs
weight: 270
url: /ar/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات في الصور ذات الألوان المعكوسة (السطوع).

```csharp
public enum InverseImageMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | يعطل التعرف الإضافي على الباركودات في الصور المعكوسة لجميع أنواع الباركود باستثناء QR Code. |
| Disabled | `1` | يعطل التعرف الإضافي على الباركودات في الصور المعكوسة. |
| Enabled | `2` | يتيح التعرف الإضافي على الباركودات في الصور المعكوسة |

## أمثلة

يعرض هذا المثال كيفية استخدام وضع InverseImage

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



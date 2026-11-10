---
title: "تعداد ComplexBackgroundMode"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode enum. الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة"
type: docs
weight: 200
url: /ar/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

الوضع الذي يتيح أو يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة.

```csharp
public enum ComplexBackgroundMode
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Auto | `0` | في الوقت الحالي هو نفسه Disabled. يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| Disabled | `1` | يعطل التعرف الإضافي على الباركودات الملونة في الصور الملونة. |
| Enabled | `2` | يتيح التعرف الإضافي على الباركودات الملونة في الصور الملونة. |

## أمثلة

يعرض هذا المثال كيفية استخدام وضع ComplexBackground

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: "QualitySettings.MaxQuality"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية QualitySettings. إعداد مسبق لجودة التعرف MaxQuality. تم تطوير هذا الإعداد المسبق للتعرف على جميع الباركودات الممكنة حتى الباركودات غير الصحيحة"
type: docs
weight: 30
url: /ar/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

إعداد مسبق لجودة التعرف MaxQuality. تم تطوير هذا الإعداد المسبق للتعرف على جميع الباركودات الممكنة، حتى الباركودات غير الصحيحة.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

إعداد مسبق لجودة التعرف MaxQuality.

## أمثلة

هذا المثال يوضح كيفية استخدام وضع MaxQuality.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### انظر أيضًا

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



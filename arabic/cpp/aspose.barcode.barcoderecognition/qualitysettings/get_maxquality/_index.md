---
title: "طريقة"
linktitle: "get_MaxQuality"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. إعداد جودة التعرف MaxQuality. تم تطوير هذا الإعداد للتعرف على جميع الباركودات الممكنة، حتى الباركودات غير الصحيحة في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_maxquality/
---
## QualitySettings::get_MaxQuality method


إعداد مسبق لجودة التعرف MaxQuality. تم تطوير هذا الإعداد المسبق للتعرف على جميع الباركود الممكنة، حتى الباركود غير الصحيحة.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_MaxQuality()
```

## ملاحظات


يعرض هذا المثال كيفية استخدام وضع MaxQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


إعداد جودة التعرف MaxQuality.
## انظر أيضًا

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

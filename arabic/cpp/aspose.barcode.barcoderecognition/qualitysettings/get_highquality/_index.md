---
title: "طريقة"
linktitle: "get_HighQuality"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. إعداد جودة التعرف HighQuality. تم تطوير هذا الإعداد للباركودات ذات الجودة المنخفضة. يسمح باكتشاف الباركودات المتضررة بشدة في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highquality/
---
## QualitySettings::get_HighQuality method


إعداد مسبق لجودة التعرف HighQuality. تم تطوير هذا الإعداد للباركودات منخفضة الجودة. يسمح باكتشاف الباركودات المتضررة بشدة.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighQuality()
```

## ملاحظات


يعرض هذا المثال كيفية استخدام وضع HighQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


إعداد جودة التعرف HighQuality.
## انظر أيضًا

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

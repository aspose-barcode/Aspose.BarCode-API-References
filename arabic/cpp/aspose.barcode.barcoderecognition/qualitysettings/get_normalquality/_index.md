---
title: "طريقة"
linktitle: "get_NormalQuality"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. إعداد مسبق لجودة التعرف NormalQuality. مناسب لمعظم الباركود في C++."
type: docs
weight: 200
url: /ar/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_normalquality/
---
## QualitySettings::get_NormalQuality method


إعداد مسبق لجودة التعرف NormalQuality. مناسب لمعظم الباركود.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_NormalQuality()
```

## ملاحظات


يعرض هذا المثال كيفية استخدام وضع NormalQuality
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


إعداد جودة التعرف NormalQuality.
## انظر أيضًا

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

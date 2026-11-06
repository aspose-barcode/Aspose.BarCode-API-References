---
title: "طريقة"
linktitle: "get_HighPerformance"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. إعداد مسبق لجودة التعرف HighPerformance. يتم التعرف على الباركود عالي الجودة بشكل جيد في هذا الوضع في C++."
type: docs
weight: 100
url: /ar/cpp/aspose.barcode.barcoderecognition/qualitysettings/get_highperformance/
---
## QualitySettings::get_HighPerformance method


إعداد مسبق لجودة التعرف HighPerformance. يتم التعرف على الباركودات عالية الجودة بشكل جيد في هذا الوضع.

```cpp
static System::SharedPtr<QualitySettings> Aspose::BarCode::BarCodeRecognition::QualitySettings::get_HighPerformance()
```

## ملاحظات


يعرض هذا المثال كيفية استخدام وضع HighPerformance
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```


إعداد مسبق لجودة التعرف HighPerformance.
## انظر أيضًا

* Class [QualitySettings](../)
* Class [QualitySettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

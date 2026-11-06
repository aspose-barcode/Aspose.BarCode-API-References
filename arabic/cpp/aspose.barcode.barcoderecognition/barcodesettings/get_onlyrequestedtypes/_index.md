---
title: "طريقة"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. تُرجع فقط أنواع الباركود المحددة صراحةً للتعرف. عندما تكون مفعلة، يتم تصفية الباركودات المعترف بها من الأنواع المتوافقة أو المكافئة الأخرى. القيمة الافتراضية هي false في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


يرجع فقط أنواع الباركود المحددة صراحةً للتعرف. عند التفعيل، يتم تصفية الباركودات المعترف بها من الأنواع المتوافقة أو المكافئة الأخرى. القيمة الافتراضية هي false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## ملاحظات


يعرض هذا المثال كيفية تقييد نتائج التعرف على أنواع الباركود المطلوبة فقط
```cpp
[C#]
//إنشاء باركود EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//التعرف على باركودات UPCA فقط (لا توجد نتائج، لأن المصدر هو EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//التعرف على الأنواع المتوافقة: EAN13، UPCA، ISSN، ISMN، ISBN (سيتم إرجاع EAN13 كمعادل UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


تُرجع فقط أنواع الباركود المحددة صراحةً للتعرف. القيمة الافتراضية هي false.
## انظر أيضًا

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

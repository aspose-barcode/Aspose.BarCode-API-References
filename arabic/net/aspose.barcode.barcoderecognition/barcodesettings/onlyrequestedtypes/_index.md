---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "خاصية BarcodeSettings. تُعيد فقط أنواع الباركود المحددة صراحةً للتعرف. عندما تكون مفعلة، يتم تصفية الباركودات المعترف بها من الأنواع المتوافقة أو المكافئة الأخرى. القيمة الافتراضية هي خطأ."
type: docs
weight: 50
url: /ar/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

تُعيد فقط أنواع الباركود المحددة صراحةً للتعرف. عندما تكون مفعلة، يتم تصفية الباركودات المعترف بها من الأنواع المتوافقة أو المكافئة الأخرى. القيمة الافتراضية هي خطأ.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

تُعيد فقط أنواع الباركود المحددة صراحةً للتعرف. القيمة الافتراضية هي خطأ.

## أمثلة

يعرض هذا المثال كيفية تقييد نتائج التعرف على أنواع الباركود المطلوبة فقط.

```csharp
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

### انظر أيضًا

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



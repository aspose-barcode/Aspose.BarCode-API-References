---
title: "فئة Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters. تخزن بيانات خاصة لباركود DotCode المعترف به في C++."
type: docs
weight: 2000
url: /ar/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


يخزن بيانات خاصة للباركود المُعترف به من نوع DotCode

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يشير إلى ما إذا كان الرمز يُستخدم لإرشاد القارئ لتفسير البيانات التالية كتعليمات لتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | يحصل على معرف باركود وضع الإلحاق المهيكل لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | يحصل على عدد باركودات وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يرجع تمثيلًا نصيًا قابلًا للقراءة للإنسان لهذا [DotCodeExtendedParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على القيم الخام لـ DotCode
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "فئة Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters. تخزن بيانات خاصة لباركود Aztec المعترف به في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


يخزن بيانات خاصة للباركود المُعترف به من نوع Aztec

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | يشير إلى ما إذا كان الرمز يُستخدم لإرشاد القارئ لتفسير البيانات التالية كتعليمات لتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | يحصل على معرّف باركود وضع الإلحاق المهيكل Aztec. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي 0. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | يحصل على عدد باركودات وضع الإلحاق المهيكل Aztec. القيمة الافتراضية هي 0. يجب أن يكون العدد قيمة من 1 إلى 26. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | يحصل على معرّف الملف لوضع الإلحاق المهيكل Aztec. القيمة الافتراضية هي سلسلة فارغة |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيل سلسلة قابلة للقراءة للبشر لهذا [AztecExtendedParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على القيم الخام لـ Aztec
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

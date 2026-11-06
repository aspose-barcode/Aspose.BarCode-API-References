---
title: "الفئة Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "الفئة Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters. تخزن بيانات خاصة للباركود المعترف به من نوع DataMatrix في C++."
type: docs
weight: 1500
url: /ar/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


تخزن بيانات خاصة للباركود المعترف به من نوع [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/)

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | يشير إلى ما إذا كان الرمز يُستخدم لإرشاد القارئ لتفسير البيانات التالية كتعليمات لتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | يحصل على معرّف [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) في وضع الإلحاق المهيكل للباركود. يبدأ المعرّف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/). القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | يحصل على معرّف [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) في وضع الإلحاق المهيكل للباركود. يبدأ المعرّف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيل سلسلة مقروءة للبشر لهذا [DataMatrixExtendedParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على القيم الأولية لـ [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/).
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

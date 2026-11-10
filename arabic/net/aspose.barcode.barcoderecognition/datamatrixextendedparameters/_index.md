---
title: "الفئة DataMatrixExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. تخزن بيانات خاصة للباركود DataMatrix المعترف به"
type: docs
weight: 220
url: /ar/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

تخزن بيانات خاصة للباركود DataMatrix المعترف به

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | يحصل على معرّف الباركود في وضع الإلحاق الهيكلي لـ DataMatrix. يبدأ المعرّف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | يحصل على عدد الباركودات في وضع الإلحاق الهيكلي لـ DataMatrix. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | يحصل على معرّف الباركود في وضع الإلحاق الهيكلي لـ DataMatrix. يبدأ المعرّف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة `DataMatrixExtendedParameters` المحددة. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | يعيد قيمة التجزئة (hash code) لهذه المثيلة. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | يعيد تمثيلاً نصيًا قابلاً للقراءة البشرية لهذا `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | يعيد قيمة تشير إلى ما إذا كانت القيمة الأولى من `DataMatrixExtendedParameters` مساوية للقيمة الثانية. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | يعيد قيمة تشير إلى ما إذا كانت القيمة الأولى من `DataMatrixExtendedParameters` مختلفة عن القيمة الثانية. |

## أمثلة

يعرض هذا المثال كيفية الحصول على القيم الأولية لـ DataMatrix

```csharp
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

### انظر أيضًا

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



---
title: "فئة AztecExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters فئة. تخزن بيانات خاصة لباركود Aztec المعترف به"
type: docs
weight: 40
url: /ar/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

تخزن بيانات خاصة لباركود Aztec المعترف به

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | يحصل على معرف (ID) باركود وضع الإلحاق الهيكلي Aztec. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | يحصل على عدد باركودات وضع الإلحاق الهيكلي Aztec. القيمة الافتراضية هي 0. يجب أن يكون العدد قيمة بين 1 و 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | يحصل على معرف الملف (File ID) لوضع الإلحاق الهيكلي Aztec. القيمة الافتراضية هي سلسلة فارغة |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `AztecExtendedParameters` المحددة. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | يعيد قيمة التجزئة (hash code) لهذه المثيلة. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | يرجع تمثيلاً نصيًا مقروءًا للإنسان لهذا `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | يرجع قيمة تشير إلى ما إذا كانت القيمة الأولى من `AztecExtendedParameters` مساوية للقيمة الثانية. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | يرجع قيمة تشير إلى ما إذا كانت القيمة الأولى من `AztecExtendedParameters` مختلفة عن القيمة الثانية. |

## أمثلة

يعرض هذا المثال كيفية الحصول على القيم الخام لباركود Aztec

```csharp
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

### انظر أيضًا

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



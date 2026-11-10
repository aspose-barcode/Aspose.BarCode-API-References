---
title: "الفئة DotCodeExtendedParameters"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters class. يخزن البيانات الخاصة لباركود DotCode المعترف به"
type: docs
weight: 250
url: /ar/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

يخزن البيانات الخاصة لباركود DotCode المعترف به

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | يحصل على المعرف (ID) لباركود وضع الإلحاق المهيكل لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة `DotCodeExtendedParameters` المحددة. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | يعيد قيمة التجزئة (hash code) لهذه المثيلة. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | يرجع قيمة تشير إلى ما إذا كانت القيمة الأولى من `DotCodeExtendedParameters` مساوية للقيمة الثانية. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | يرجع قيمة تشير إلى ما إذا كانت القيمة الأولى من `DotCodeExtendedParameters` مختلفة عن القيمة الثانية. |

## أمثلة

يعرض هذا المثال كيفية الحصول على القيم الخام لـ DotCode.

```csharp
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

### انظر أيضًا

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)



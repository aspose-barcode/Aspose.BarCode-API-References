---
title: "الفئة MaxiCodeCodetext"
second_title: "مرجع API لـ Aspose.BarCode for .NET"
description: "الفئة Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext. الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode"
type: docs
weight: 680
url: /ar/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | يحصل أو يعيّن ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | يحصل أو يعيّن وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | يحصل على نوع الباركود. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | يبني نص الرمز |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | يحصل على وضع MaxiCode. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | يُهيئ المثيلة من نص الرمز المُنشأ. |

## أمثلة

يوضح هذا المثال كيفية فك تشفير نص MaxiCode الخام إلى كائن MaxiCodeCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### انظر أيضًا

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



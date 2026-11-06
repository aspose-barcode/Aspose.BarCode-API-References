---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext فئة"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext فئة. الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode في C++."
type: docs
weight: 1600
url: /ar/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز MaxiCode.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | ينشئ نص الترميز |
| virtual [GetMode](./getmode/)() const | يحصل على وضع MaxiCode. |
| virtual [InitFromString](./initfromstring/)(System::String) | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | يضبط وضع ترميز MaxiCode. القيمة الافتراضية: تلقائي. |
## ملاحظات


يوضح هذا المثال كيفية فك تشفير نص MaxiCode الخام إلى مثيل [MaxiCodeCodetext](./).
```cpp
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

## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

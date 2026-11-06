---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext فئة"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext فئة. الفئة الأساسية للترميز وفك الترميز للنص المضمن في رمز HIBC LIC في C++."
type: docs
weight: 800
url: /ar/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


الفئة الأساسية لتشفير وفك تشفير النص المضمن في رمز HIBC LIC.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | يحصل على نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | ينشئ نص الترميز |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
## ملاحظات


يوضح هذا المثال كيفية فك ترميز نص الترميز الخام لـ HIBC LIC إلى مثيل [HIBCLICComplexCodetext](./).
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

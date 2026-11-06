---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext فئة"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext فئة. فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية في C++."
type: docs
weight: 900
url: /ar/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [HIBCLICPrimaryDataCodetext](./) المحددة. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | يحصل على نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | يحدد البيانات الأولية. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | يحدد البيانات الأولية. |
## ملاحظات


يعرض هذا المثال كيفية تشفير وفك تشفير HIBC LIC باستخدام [HIBCLICPrimaryDataCodetext](./).
```cpp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

## انظر أيضًا

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

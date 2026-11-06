---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext فئة"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext فئة. فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الأولية والثانوية.

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [HIBCLICCombinedCodetext](./) المحددة. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | يحصل على نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [get_PrimaryData](./get_primarydata/)() const | يحدد البيانات الأولية. |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | يحدد البيانات الثانوية والبيانات الإضافية التكميلية. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | يحدد البيانات الأولية. |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | يحدد البيانات الثانوية والبيانات الإضافية التكميلية. |
## ملاحظات


يوضح هذا المثال كيفية تشفير وفك تشفير HIBC LIC باستخدام [HIBCLICCombinedCodetext](./).
```cpp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

## انظر أيضًا

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

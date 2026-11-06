---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext فئة"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext فئة. فئة لتشفير وفك تشفير النص المضمّن في رمز HIBC LIC الذي يخزن البيانات الثانوية في C++."
type: docs
weight: 1000
url: /ar/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الثانوية.

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [HIBCLICSecondaryAndAdditionalDataCodetext](./) المحددة. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | يحصل على نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | يحدد البيانات الثانوية والإضافية التكميلية. |
| [get_LinkCharacter](./get_linkcharacter/)() const | يحدد حرف الرابط. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود. يمكن ترميز نص HIBC LIC باستخدام أنواع الترميز HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | يحدد البيانات الثانوية والإضافية التكميلية. |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | يحدد حرف الرابط. |
## ملاحظات


///

هذا المثال يوضح كيفية ترميز وفك ترميز HIBC LIC باستخدام [HIBCLICSecondaryAndAdditionalDataCodetext](./).
```cpp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

## انظر أيضًا

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

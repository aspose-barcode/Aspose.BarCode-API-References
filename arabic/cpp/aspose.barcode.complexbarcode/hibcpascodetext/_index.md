---
title: "فئة Aspose::BarCode::ComplexBarcode::HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::ComplexBarcode::HIBCPASCodetext. فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS في C++."
type: docs
weight: 1100
url: /ar/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | يضيف سجلًا جديدًا |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | يضيف سجلًا جديدًا |
| [Clear](./clear/)() | يمسح قائمة السجلات |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [HIBCPASCodetext](./) المحددة. |
| [get_BarcodeType](./get_barcodetype/)() const | يحصل على نوع الباركود. يمكن ترميز نص HIBC PAS باستخدام أنواع الترميز HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCDataMatrixPAS و HIBCQRPAS. القيمة الافتراضية: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | يحدد موقع البيانات. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ينشئ نص الترميز |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [GetRecords](./getrecords/)() | يحصل على قائمة السجلات |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ المثيلة من نص الترميز المُنشأ. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | يضبط نوع الباركود. يمكن ترميز نص HIBC PAS باستخدام أنواع الترميز HIBCCode39PAS، HIBCCode128PAS، HIBCAztec:PAS، HIBCDataMatrixPAS و HIBCQRPAS. القيمة الافتراضية: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | يحدد موقع البيانات. |
## ملاحظات


يعرض هذا المثال كيفية ترميز وفك ترميز HIBC PAS باستخدام [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

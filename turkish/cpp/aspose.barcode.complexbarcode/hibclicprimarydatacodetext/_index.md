---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext sınıfı"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext sınıfı. HIBC LIC kodunda gömülü metni kodlamak ve çözmek için sınıf, C++'da birincil verileri depolar."
type: docs
weight: 900
url: /tr/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Birincil verileri saklayan HIBC LIC koduna gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Belirtilen [HIBCLICPrimaryDataCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Barkod tipini alır. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Birincil verileri tanımlar. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Barkod tipini ayarlar. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Birincil verileri tanımlar. |
## Açıklamalar


Bu örnek, [HIBCLICPrimaryDataCodetext](./) kullanarak HIBC LIC'yi nasıl kodlayıp çözeceğinizi gösterir.
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

## Ayrıca Bakınız

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

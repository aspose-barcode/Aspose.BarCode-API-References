---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext sınıfı"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext sınıfı. C++'da birincil ve ikincil verileri depolayan HIBC LIC koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


Birincil ve ikincil verileri saklayan HIBC LIC koduna gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Belirtilen [HIBCLICCombinedCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Barkod tipini alır. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [get_PrimaryData](./get_primarydata/)() const | Birincil verileri tanımlar. |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | İkincil ve ek destek verilerini tanımlar. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Barkod tipini ayarlar. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | Birincil verileri tanımlar. |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | İkincil ve ek destek verilerini tanımlar. |
## Açıklamalar


Bu örnek, [HIBCLICCombinedCodetext](./) kullanarak HIBC LIC'yi nasıl kodlayıp çözeceğinizi gösterir.
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

## Ayrıca Bakınız

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

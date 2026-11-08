---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext sınıfı"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext sınıfı. C++'da ikincil verileri depolayan HIBC LIC koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 1000
url: /tr/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


İkincil verileri saklayan HIBC LIC koduna gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen [HIBCLICSecondaryAndAdditionalDataCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Barkod tipini alır. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | İkincil ve ek destek verileri tanımlar. |
| [get_LinkCharacter](./get_linkcharacter/)() const | Bağlantı karakterini tanımlar. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Barkod tipini ayarlar. HIBC LIC kod metni, HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC ve HIBCQRLIC kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | İkincil ve ek destek verileri tanımlar. |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | Bağlantı karakterini tanımlar. |
## Açıklamalar


///

Bu örnek, HIBC LIC'yi [HIBCLICSecondaryAndAdditionalDataCodetext](./) kullanarak nasıl kodlayıp çözeceğinizi gösterir.
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

## Ayrıca Bakınız

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

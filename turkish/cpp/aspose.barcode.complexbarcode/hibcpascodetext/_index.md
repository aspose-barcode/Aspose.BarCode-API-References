---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext sınıfı"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext sınıfı. C++'ta HIBC PAS koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 1100
url: /tr/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


HIBC PAS koduna gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Yeni kayıt ekler |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Yeni kayıt ekler |
| [Clear](./clear/)() | Kayıt listesini temizler |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen [HIBCPASCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_BarcodeType](./get_barcodetype/)() const | Barkod tipini alır. HIBC PAS kod metni HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS ve HIBCQRPAS kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Veri konumunu belirler. |
| [GetBarcodeType](./getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetRecords](./getrecords/)() | Kayıt listesini alır |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Barkod tipini ayarlar. HIBC PAS kod metni HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS ve HIBCQRPAS kodlama türleri kullanılarak kodlanabilir. Varsayılan değer: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Veri konumunu belirler. |
## Açıklamalar


Bu örnek, [HIBCPASCodetext](./) kullanarak HIBC PAS'ı nasıl kodlayıp çözeceğinizi gösterir.
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

## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

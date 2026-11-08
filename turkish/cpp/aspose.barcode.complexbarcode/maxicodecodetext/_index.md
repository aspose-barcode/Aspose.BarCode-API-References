---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext sınıfı"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext sınıfı. C++'da MaxiCode koduna gömülü metni kodlamak ve çözmek için temel sınıf."
type: docs
weight: 1600
url: /tr/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


MaxiCode kodunda gömülü metni kodlamak ve çözmek için temel sınıf.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik. |
| [GetBarcodeType](./getbarcodetype/)() override | Barkod tipini alır. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Kod metnini oluşturur |
| virtual [GetMode](./getmode/)() const | MaxiCode modunu alır. |
| virtual [InitFromString](./initfromstring/)(System::String) | Oluşturulan kod metninden örneği başlatır. |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik. |
## Açıklamalar


Bu örnek, ham MaxiCode kod metnini [MaxiCodeCodetext](./) örneğine nasıl çözeceğinizi gösterir.
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

## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

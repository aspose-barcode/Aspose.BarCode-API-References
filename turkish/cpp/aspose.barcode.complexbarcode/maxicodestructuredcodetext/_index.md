---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext sınıfı"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext sınıfı. C++'ta mod 2 ve 3 için MaxiCode koduna gömülü metni kodlamak ve çözmek için temel sınıf."
type: docs
weight: 2200
url: /tr/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


Mod 2 ve 3 için MaxiCode kodunda gömülü metni kodlamak ve çözmek için temel sınıf.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen [MaxiCodeStructuredCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_CountryCode](./get_countrycode/)() const | 3 haneli ülke kodunu tanımlar. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik. |
| [get_PostalCode](./get_postalcode/)() const | Posta kodunu tanımlar. Mod 2'de 9 hane, mod 3'te 6 alfanümerik sembol olmalıdır. |
| [get_SecondMessage](./get_secondmessage/)() const | Barkodun ikinci mesajını tanımlar. |
| [get_ServiceCategory](./get_servicecategory/)() const | 3 haneli hizmet kategorisini tanımlar. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | MaxiCode modunu alır. |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | 3 haneli ülke kodunu tanımlar. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik. |
| [set_PostalCode](./set_postalcode/)(System::String) | Posta kodunu tanımlar. Mod 2'de 9 hane, mod 3'te 6 alfanümerik sembol olmalıdır. |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Barkodun ikinci mesajını tanımlar. |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | 3 haneli hizmet kategorisini tanımlar. |
## Açıklamalar


Bu örnek, ham MaxiCode kod metnini [MaxiCodeStructuredCodetext](./) örneğine nasıl çözüleceğini gösterir.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

## Ayrıca Bakınız

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

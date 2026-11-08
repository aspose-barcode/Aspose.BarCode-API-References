---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 class"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 class. C++'de mod 2 için MaxiCode koduna gömülü metni kodlamak ve kodunu çözmek için sınıf."
type: docs
weight: 1700
url: /tr/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


Mod 2 için MaxiCode kodunda gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | Bu örneğin belirtilen [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | 3 haneli ülke kodunu tanımlar. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik. |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | Posta kodunu tanımlar. Mod 2'de 9 hane, mod 3'te 6 alfanümerik sembol olmalıdır. |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | Barkodun ikinci mesajını tanımlar. |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | 3 haneli hizmet kategorisini tanımlar. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetMode](./getmode/)() const override | MaxiCode modunu alır. |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | 3 haneli ülke kodunu tanımlar. |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik. |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | Posta kodunu tanımlar. Mod 2'de 9 hane, mod 3'te 6 alfanümerik sembol olmalıdır. |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | Barkodun ikinci mesajını tanımlar. |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | 3 haneli hizmet kategorisini tanımlar. |
## Açıklamalar


Bu örnek, mod 2 için MaxiCode kod metnini nasıl kodlayıp çözeceğinizi gösterir.
```cpp
[C#]
//Mod 2 ile standart ikinci mesaj
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Mod 2 ile yapılandırılmış ikinci mesaj
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Standart ikinci mesaj ile ham kod metninin çözülmesi
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//Yapılandırılmış ikinci mesaj ile ham kod metninin çözülmesi
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## Ayrıca Bakınız

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext sınıfı"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStandardCodetext sınıfı. Mod 4, 5 ve 6 için MaxiCode kod metnini kodlamak ve çözmek amacıyla C++'da kullanılan sınıf."
type: docs
weight: 2000
url: /tr/cpp/aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class


Mod 4, 5 ve 6 için MaxiCode kod metnini kodlamak ve çözmek için sınıf.

```cpp
class MaxiCodeStandardCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Belirtilen [MaxiCodeStandardCodetext](./) değerine eşit olup olmadığını gösteren bir değer döndürür. |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI kodlamasını alır. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | Bir MaxiCode kodlama modunu alır. Varsayılan değer: Otomatik. |
| [get_Message](./get_message/)() const | Mesajı alır. |
| [get_Mode](./get_mode/)() | MaxiCode modunu alır. Standart kod metni yalnızca mod 4, 5 ve 6 ile kullanılabilir. |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Kod metnini oluşturur |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [GetMode](./getmode/)() const override | MaxiCode modunu alır. |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden örneği başlatır. |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/)() |  |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI kodlamasını ayarlar. MaxiCodeEncodeMode otomatik olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | Bir MaxiCode kodlama modunu ayarlar. Varsayılan değer: Otomatik. |
| [set_Message](./set_message/)(System::String) | Mesajı ayarlar. |
| [set_Mode](./set_mode/)(Generation::MaxiCodeMode) | MaxiCode modunu ayarlar. Standart kod metni yalnızca mod 4, 5 ve 6 ile kullanılabilir. |
## Açıklamalar


//Mod 4 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode4; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mod 5 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode5; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); } //Mod 6 [MaxiCodeStandardCodetext](./) maxiCodeCodetext = new [MaxiCodeStandardCodetext()](./maxicodestandardcodetext/); maxiCodeCodetext.Mode = MaxiCodeMode.Mode6; maxiCodeCodetext.Message = "Test message"; using ([ComplexBarcodeGenerator](../complexbarcodegenerator/) complexGenerator = new [ComplexBarcodeGenerator](../complexbarcodegenerator/)(maxiCodeCodetext.GetConstructedCodetext()) { complexGenerator.GenerateBarCodeImage(); }
## Ayrıca Bakınız

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)

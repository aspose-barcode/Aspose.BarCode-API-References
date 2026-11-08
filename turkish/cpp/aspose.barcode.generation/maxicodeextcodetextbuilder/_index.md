---
title: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder class"
linktitle: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::MaxiCodeExtCodetextBuilder sınıfının C++'da nasıl kullanılacağını."
type: docs
weight: 3500
url: /tr/cpp/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class




```cpp
class MaxiCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| virtual [Clear](../extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genişletilmiş kod metni listesinden Genişletilmiş kod metni üretir. |
## Açıklamalar


MaxiCodeEncodeMode'un ExtendedCodetext Modu için MaxiCode barkodları için genişletilmiş kod metni oluşturucu

Görünür metni yönetim karakterlerini kaldırmak için ayarlamak üzere [BarcodeGenerator](../barcodegenerator/) sınıfının TwoDDisplayText özelliğini kullanın.

Bu örnek, [MaxiCodeExtCodetextBuilder](./) öğesinin Genişletilmiş Modda nasıl kullanılacağını gösterir.
```cpp
[C#]
//kod metni oluştur
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da Aspose::BarCode::Generation::DotCodeExtCodetextBuilder sınıfını nasıl kullanılır."
type: docs
weight: 2100
url: /tr/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Genişletilmiş kodmetni öğelerine FNC1 format tanımlayıcısı ekler |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Genişletilmiş kodmetni öğelerine FNC3 okuyucu başlatmasını ekler |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Genişletilmiş kodmetni öğelerine FNC3 sembol ayırıcı ekler |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Genişletilmiş kodmetni öğelerine yapılandırılmış ekleme modunu ekler |
| virtual [Clear](../extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genişletilmiş kod metni listesinden Genişletilmiş kod metni üretir. |
## Açıklamalar


DotCodeEncodeMode'un ExtendedCodetext Modu için 2D DotCode barkodları için genişletilmiş kodmetni oluşturucu


```cpp
[C#]
//Genişletilmiş kod metni modu
//kod metni oluştur
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

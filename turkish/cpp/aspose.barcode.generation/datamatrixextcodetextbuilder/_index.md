---
title: "Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder sınıfı"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder sınıfının nasıl kullanılacağını."
type: docs
weight: 1900
url: /tr/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Tanımlı kodlama moduyla kodmetnini genişletilmiş kodmetni öğelerine ekler |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı içeren kodmetnini ekler |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| virtual [Clear](../extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genişletilmiş kod metni listesinden Genişletilmiş kod metni üretir. |
## Açıklamalar


EncodeMode'un ExtendedCodetext Modu için 2D DataMatrix barkodları için genişletilmiş kodmetni üreteci


```cpp
[C#]
//Genişletilmiş kod metni modu

//kod metni oluştur
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

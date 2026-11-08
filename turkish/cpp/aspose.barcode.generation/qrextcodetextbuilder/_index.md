---
title: "Aspose::BarCode::Generation::QrExtCodetextBuilder class"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'ta Aspose::BarCode::Generation::QrExtCodetextBuilder sınıfını nasıl kullanılır."
type: docs
weight: 4300
url: /tr/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Belirtilen QR sıkıştırma moduyla kod metnini genişletilmiş kod metni öğelerine ekler. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | FNC1'i ilk konuma ayarlar. Daha önce ayarlanmış başka bir FNC1 modu varsa, onun yerine geçer. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Group Separator (GS - '\\u001D') öğelerini genişletilmiş kodmetni öğelerine ekler. |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | FNC1'i ikinci konuma ayarlar. Daha önce ayarlanmış başka bir FNC1 modu varsa, onun yerine geçer. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| [Clear](./clear/)() override | Genişletilmiş kod metni öğelerini temizler |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Genişletilmiş kod metni listesinden Genişletilmiş kod metni üretir. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Açıklamalar


EncodeMode'un ExtendedCodetext Modu için 2D QR barkodları için genişletilmiş kodmetni üreticisi.

Görünür metni yönetim karakterlerini kaldırmak için ayarlamak üzere [BarcodeGenerator](../barcodegenerator/) sınıfının TwoDDisplayText özelliğini kullanın.

Bu örnek, Genişletilmiş Modda FNC1'in ilk konumunu nasıl kullanacağınızı gösterir.
```cpp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//kod metni üret
string codetext = TextBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Bu örnek, Genişletilmiş Modda FNC1'in ikinci konumunu nasıl kullanacağınızı gösterir.
```cpp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//kod metni üret
string codetext = TextBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Bu örnek, Genişletilmiş Modda çoklu ECI modunu nasıl kullanacağınızı gösterir.
```cpp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//kod metni üret
string codetext = TextBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

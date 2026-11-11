---
title: "Class QrExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.QrExtCodetextBuilder sınıfı. EncodeMode'un ExtendedCodetext Modu için 2D QR barkodları için genişletilmiş kod metni oluşturucu"
type: docs
weight: 1630
url: /tr/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

EncodeMode'un ExtendedCodetext Modu için 2D QR barkodları için genişletilmiş kod metni oluşturucu

Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Belirtilen QR sıkıştırma modu ile kod metnini genişletilmiş kod metni öğelerine ekler. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | FNC1'i ilk konuma ayarlar. Daha önce başka bir FNC1 modu ayarlanmışsa, yerine geçer. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Genişletilmiş kod metni öğelerine Grup Ayırıcı (GS - '\\u001D') ekler |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | FNC1'i ikinci konuma ayarlar. Daha önce başka bir FNC1 modu ayarlanmışsa, yerine geçer. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Genişletilmiş kod metni listesinden genişletilmiş kod metni oluşturur. |

## Örnekler

Bu örnek, Genişletilmiş Modda FNC1'in ilk konumunun nasıl kullanılacağını gösterir.

```csharp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//kod metni oluştur
string codetext = TextBuilder.GetExtendedCodetext();

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Bu örnek, Genişletilmiş Modda FNC1'in ikinci konumunun nasıl kullanılacağını gösterir.

```csharp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//kod metni oluştur
string codetext = TextBuilder.GetExtendedCodetext();

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Bu örnek, Genişletilmiş Modda çoklu ECI modunun nasıl kullanılacağını gösterir.

```csharp
[C#]
//kod metni oluştur
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//kod metni oluştur
string codetext = TextBuilder.GetExtendedCodetext();

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



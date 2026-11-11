---
title: "Sınıf MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder sınıfı. MaxiCode barkodları için MaxiCodeEncodeMode'un ExtendedCodetext Modu'na yönelik genişletilmiş kod metni oluşturucu"
type: docs
weight: 1470
url: /tr/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

MaxiCodeEncodeMode'un ExtendedCodetext Modu için MaxiCode barkodları için genişletilmiş kod metni oluşturucu

Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Genişletilmiş kod metni listesinden genişletilmiş kod metni oluşturur. |

## Örnekler

Bu örnek, MaxiCodeExtCodetextBuilder'ı Genişletilmiş Modda nasıl kullanacağınızı gösterir.

```csharp
[C#]
//kod metni oluştur
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//kod metni oluştur
string codetext = textBuilder.GetExtendedCodetext();    

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



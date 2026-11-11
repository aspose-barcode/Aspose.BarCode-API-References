---
title: "Sınıf AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder sınıfı. Aztec barkodları için AztecEncodeMode'un ExtendedCodetext Modu için genişletilmiş kod metni üreticisi."
type: docs
weight: 950
url: /tr/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

AztecEncodeMode'un ExtendedCodetext Modu için Aztec barkodları için genişletilmiş kod metni üreticisi

Görünür metni ayarlamak ve yönetim karakterlerini kaldırmak için BarcodeGenerator'ın TwoDDisplayText özelliğini kullanın.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Genişletilmiş kod metni listesinden genişletilmiş kod metni oluşturur. |

## Örnekler

Bu örnek, AztecExtCodetextBuilder'ı Genişletilmiş Modda nasıl kullanacağınızı gösterir.

```csharp
[C#]
//kod metni oluştur
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//kod metni oluştur
string codetext = textBuilder.GetExtendedCodetext();    

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Sınıf DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.DotCodeExtCodetextBuilder sınıfı. DotCodeEncodeMode'un ExtendedCodetext Modu için 2D DotCode barkodları için genişletilmiş kod metni oluşturucu"
type: docs
weight: 1250
url: /tr/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

DotCodeEncodeMode'un ExtendedCodetext Modu için 2D DotCode barkodları için genişletilmiş kod metni oluşturucu

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Genişletilmiş kod metni öğelerine FNC1 format tanımlayıcısı ekler |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Genişletilmiş kod metni öğelerine FNC3 okuyucu başlatmasını ekler |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Genişletilmiş kod metni öğelerine FNC3 sembol ayırıcı ekler |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Genişletilmiş kod metni öğelerine yapılandırılmış ekleme modunu ekler |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Genişletilmiş kod metni listesinden genişletilmiş kod metni oluşturur. |

## Örnekler

```csharp
[C#]
//Extended kod metni modu
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

//kod metni oluştur
string codetext = textBuilder.GetExtendedCodetext();    

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



---
title: "Sınıf DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder sınıfı. 2D DataMatrix barkodları için EncodeMode'un ExtendedCodetext Modu için genişletilmiş kod metni üreticisi."
type: docs
weight: 1210
url: /tr/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

EncodeMode'un ExtendedCodetext Modu için 2D DataMatrix barkodları için genişletilmiş kod metni oluşturucu

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Tanımlı kodlama moduyla kod metnini genişletilmiş kod metni öğelerine ekler |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Genişletilmiş Kanal Tanımlayıcısı ile kod metni ekler |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Tanımlı kodlama modu ile Genişletilmiş Kanal Tanımlayıcısı içeren kod metnini ekler |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Düz kod metnini genişletilmiş kod metni öğelerine ekler |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Genişletilmiş kod metni öğelerini temizler |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Genişletilmiş kod metni listesinden genişletilmiş kod metni oluşturur. |

## Örnekler

```csharp
[C#]
//Extended kod metni modu

//kod metni oluştur
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//kod metni oluştur
string codetext = textBuilder.GetExtendedCodetext();    

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



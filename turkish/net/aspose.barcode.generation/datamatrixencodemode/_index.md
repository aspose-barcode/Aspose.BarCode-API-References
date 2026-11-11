---
title: "Enum DataMatrixEncodeMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.DataMatrixEncodeMode enum. DataMatrix kodlayıcılarının kodlama modu varsayılan olarak Auto'dur."
type: docs
weight: 1200
url: /tr/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

DataMatrix kodlayıcısının kodlama modu, varsayılan olarak Otomatik

```csharp
public enum DataMatrixEncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Auto modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| ASCII | `1` | Her bayt için bir alfanümerik veya iki sayısal karakter kodlar. |
| C40 | `8` | C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar. |
| Text | `9` | Text kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar. |
| EDIFACT | `10` | EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez. |
| ANSIX12 | `11` | ANSI X12 kodlamasını kullanır. |
| Extended | `13` | ExtendedCodetext modu, kod metninde kodlama şemalarını ve ECI kodlamalarını manuel olarak değiştirmeye izin verir. |
| Base256 | `14` | 8 bit değerleri kodla |
| Binary | `15` | Binary modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | `16` | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |

## Örnekler

Bu örnek, Extended Mod'da kod metninin nasıl yapılacağını gösterir.

```csharp
[C#]
//Auto modu
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes modu
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


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
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



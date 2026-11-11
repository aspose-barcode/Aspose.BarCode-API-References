---
title: "Enum DotCodeEncodeMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.DotCodeEncodeMode enum. DotCode barkodları için kodlama modu"
type: docs
weight: 1240
url: /tr/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

DotCode barkodları için kodlama modu.

```csharp
public enum DotCodeEncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Auto modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| Binary | `3` | Binary modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | `4` | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |
| Extended | `5` | Çoklu ECI modlarını destekleyen genişletilmiş mod. |

## Örnekler

```csharp
[C#]
//Makrolarla otomatik mod
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Auto modu
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bytes modu
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended kod metni modu
//kod metni oluştur
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//kod metni oluştur
string codetext = textBuilder.GetExtendedCodetext();    

//oluştur
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



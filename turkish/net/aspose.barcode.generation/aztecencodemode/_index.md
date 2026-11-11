---
title: "AztecEncodeMode enumı"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.AztecEncodeMode enumı. Aztec barkodları için kodlama modu"
type: docs
weight: 940
url: /tr/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Aztec barkodları için kodlama modu.

```csharp
public enum AztecEncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Auto modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| Extended | `3` | Çoklu ECI modlarını destekleyen genişletilmiş mod. |
| Binary | `4` | Binary modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | `5` | ECI modunda, tüm mesaj belirtilen ECIEncoding kodlamasında bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |

## Örnekler

```csharp
[C#]
//Auto modu
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Extended modu
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
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



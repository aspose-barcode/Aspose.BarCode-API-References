---
title: "enum"
linktitle: "AztecEncodeMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'de Aztec barkodları için kodlama modu."
type: docs
weight: 5300
url: /tr/cpp/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enum


Aztec barkodları için kodlama modu.

```cpp
enum class AztecEncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Auto modunda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| Genişletilmiş | 3 |  |
| İkili | 4 | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | 5 | ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |

## Açıklamalar



```cpp
[C#]
//Otomatik mod
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

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

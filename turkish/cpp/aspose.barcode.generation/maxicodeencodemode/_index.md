---
title: "enum"
linktitle: "MaxiCodeEncodeMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'da MaxiCode barkodları için kodlama modu."
type: docs
weight: 7500
url: /tr/cpp/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enum


MaxiCode barkodları için kodlama modu.

```cpp
enum class MaxiCodeEncodeMode
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
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bayt modu
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Genişletilmiş kod metni modu
//kod metni oluştur
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

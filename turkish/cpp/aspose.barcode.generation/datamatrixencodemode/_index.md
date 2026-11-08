---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. DataMatrix kodlayıcısının kodlama modu, C++'ta varsayılan olarak Auto."
type: docs
weight: 6300
url: /tr/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


DataMatrix kodlayıcısının kodlama modu, varsayılan olarak Otomatik

```cpp
enum class DataMatrixEncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Auto modunda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| ASCII | 1 | Her bayt başına bir alfanümerik veya iki sayısal karakter kodlar. |
| C40 | 8 | C40 kodlamasını kullanır. Büyük harf alfanümerik, küçük harf ve özel karakterleri kodlar. |
| Metin | 9 | Metin kodlamasını kullanır. Küçük harf alfanümerik, büyük harf ve özel karakterleri kodlar. |
| EDIFACT | 10 | EDIFACT kodlamasını kullanır. Karakter başına altı bit kullanır, rakamları, büyük harfleri ve birçok noktalama işaretini kodlar, ancak küçük harfleri desteklemez. |
| ANSIX12 | 11 | ANSI X12 kodlamasını kullanır. |
| Genişletilmiş | 13 |  |
| Base256 | 14 | 8 bit değerleri kodla |
| İkili | 15 | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | 16 | ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |

## Açıklamalar


Bu örnek, Genişletilmiş Modda kod metni nasıl yapılacağını gösterir.
```cpp
[C#]
//Otomatik mod
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Bayt modu
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


//Genişletilmiş kod metni modu
//kod metni oluştur
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//kod metni üret
string codetext = textBuilder.GetExtendedCodetext();

//üret
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

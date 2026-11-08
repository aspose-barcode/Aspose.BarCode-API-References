---
title: "metot"
linktitle: "SetCodeText"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. C++'ta kod metnini bayt dizisi olarak ayarlar."
type: docs
weight: 700
url: /tr/cpp/aspose.barcode.generation/barcodegenerator/setcodetext/
---
## BarcodeGenerator::SetCodeText(System::ArrayPtr\<uint8_t\>) method


Kod metnini bayt dizisi olarak ayarla.

```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::ArrayPtr<uint8_t> codeBytes)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeBytes | System::ArrayPtr\<uint8_t\> | Kod metninin baytları |

## Ayrıca Bakınız

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | System::String | CodeText dizesi |
| kodlama | System::SharedPtr\<System::Text::Encoding\> | Uygulanan kodlama |
## Açıklamalar


Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyorsa, fonksiyon otomatik olarak bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler.

Bu işlev yalnızca 2D barkodlarla (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR vb.) kullanılmak üzere tasarlanmıştır. Ulusal veya özel kodlamalar kullanarak Unicode metnin manuel olarak kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) kodlaması önerilir.

Bu işlevi 1D barkodlar, GS1 uyumlu barkodlar (2D dahil) veya HIBC barkodlar (2D dahil) ile kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.


Bu örnek, farklı kodlamalar kullanarak 2D barkodlar için Unicode kodlu metni ayarlayan **SetCodeText** kullanımını gösterir:


```cpp
[C#]
//QR Kod metnini UTF-8 ve BOM ile kodla
using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
{
    gen.SetCodeText("車種名", Encoding.UTF8);
    gen.Save("barcode.png", BarCodeImageFormat.Png);
}
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //DataMatrix metnini Shift-JIS (Japon kodlaması) ile kodla
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## Ayrıca Bakınız

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
## BarcodeGenerator::SetCodeText(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) method




```cpp
void Aspose::BarCode::Generation::BarcodeGenerator::SetCodeText(System::String codeText, System::SharedPtr<System::Text::Encoding> encoding, bool insertBOM)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| codeText | System::String | CodeText dizesi |
| kodlama | System::SharedPtr\<System::Text::Encoding\> | Uygulanan kodlama |
| insertBOM | bool | Belirtilen kodlama desteklediğinde (ör. UTF-8, UTF-16, UTF-32) bir byte order mark (BOM) eklenip eklenmeyeceğini gösterir. **true** olarak ayarlanırsa BOM eklenir; **false** ise kodlama normalde bir BOM kullansa bile eklenmez. |
## Açıklamalar


Belirtilen **encoding** kullanılarak Unicode **codeText**'i bir bayt dizisine kodlar. UTF-8 en yaygın kullanılan kodlamadır. Kodlama bunu destekliyor ve **insertBOM** **true** olarak ayarlanmışsa, fonksiyon bir [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding) ekler.

Bu işlev yalnızca 2D barkodlarla (ör. Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR vb.) kullanılmak üzere tasarlanmıştır. Ulusal veya özel kodlamalar kullanarak Unicode metnin manuel olarak kodlanmasını sağlar; ancak bu yöntem modern uygulamalarda eski kabul edilir. Modern kullanım durumları için Unicode verileri için [ECI](https://en.wikipedia.org/wiki/Extended_Channel_Interpretation) kodlaması önerilir.

Bu işlevi 1D barkodlar, GS1 uyumlu barkodlar (2D dahil) veya HIBC barkodlar (2D dahil) ile kullanmak, ilgili barkod standartları tarafından desteklenmez ve öngörülemeyen sonuçlara yol açabilir.


Bu örnek, 2D barkodlar için **SetCodeText**'i BOM ile veya BOM olmadan nasıl kullanılacağını gösterir.


```cpp
[C#]
    //Kod metnini UTF-8 BOM ile kodlayın
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, true);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);

    //Kod metnini UTF-8 BOM olmadan kodlayın
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.QR))
    {
        gen.SetCodeText("車種名", Encoding.UTF8, false);
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.QR))
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
```

## Ayrıca Bakınız

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

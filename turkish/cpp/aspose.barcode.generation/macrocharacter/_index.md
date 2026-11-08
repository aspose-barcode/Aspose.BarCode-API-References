---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. Makro Karakterler 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. 05 Makro karakteri, çözülen veri başlığı olarak \"[)>\\u001E05\\u001D\" ve çözülen veri kuyruğu olarak \"\\u001E\\u0004\" şeklinde çevrilir. 06 Makro karakteri, çözülen veri başlığı olarak \"[)>\\u001E06\\u001D\" ve çözülen veri kuyruğu olarak \"\\u001E\\u0004\" şeklinde C++'de çevrilir."
type: docs
weight: 7300
url: /tr/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. 05 Macro karakteri, çözülen veri başlığı olarak \"[)>\\u001E05\\u001D\" ve çözülen veri sonu olarak \"\\u001E\\u0004\" olarak çevrilir. 06 Macro karakteri, çözülen veri başlığı olarak \"[)>\\u001E06\\u001D\" ve çözülen veri sonu olarak \"\\u001E\\u0004\" olarak çevrilir.

```cpp
enum class MacroCharacter
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Yok | 0 | Makro Karakterlerin hiçbiri barkod verisine eklenmez |
| Macro05 | 5 | 05 Makro karakteri, barkod verisine ilk konumda eklenir. GS1 Veri Tanımlayıcısı ISO 15434 Karakteri, çözülen veri başlığı olarak "[)>\u001E05\u001D" ve çözülen veri kuyruğu olarak "\u001E\u0004" şeklinde çevrilir. |
| Macro06 | 6 | 06 Makro karakteri, barkod verisine ilk konumda eklenir. ASC MH10 Veri Tanımlayıcısı ISO 15434 Karakteri, çözülen veri başlığı olarak "[)>\u001E06\u001D" ve çözülen veri kuyruğu olarak "\u001E\u0004" şeklinde çevrilir. |

## Açıklamalar


Bu örnekler, MicroPdf417 ve DataMatrix'te Makro Karakterlerin nasıl kodlanacağını gösterir.
```cpp
[C#]
//ISO 15434 formatında "(10)123ABC(10)123ABC" gibi otomatik tanımlı GS1 mesajı oluşturmak için şunlara ihtiyacınız var:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//MicroPdf417'yi 05 Makro ile şu dizeyi kodlar: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//MicroPdf417'yi 06 Makro ile şu dizeyi kodlar: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

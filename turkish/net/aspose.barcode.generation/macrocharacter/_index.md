---
title: "Enum MacroCharacter"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.MacroCharacter enum. Macro Characters 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. 05 Macro karakteri, çözülen veri başlığı olarak u001E05u001D ve çözülen veri kuyruğu olarak u001Eu0004 ile çevrilir. 06 Macro karakteri, çözülen veri başlığı olarak u001E06u001D ve çözülen veri kuyruğu olarak u001Eu0004 ile çevrilir."
type: docs
weight: 1450
url: /tr/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. 05 Makro karakter "[)&gt;\u001E05\u001D" olarak çözülen veri başlığına ve "\u001E\u0004" olarak çözülen veri sonuna çevrilir. 06 Makro karakter "[)&gt;\u001E06\u001D" olarak çözülen veri başlığına ve "\u001E\u0004" olarak çözülen veri sonuna çevrilir.

```csharp
public enum MacroCharacter
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| None | `0` | Macro Characters hiçbirisi barkod verisine eklenmez |
| Macro05 | `5` | 05 Macro karakteri, barkod verisine ilk konumda eklenir. GS1 Veri Tanımlayıcısı ISO 15434 Karakteri, çözülen veri başlığı olarak "[)&gt;\u001E05\u001D" ve çözülen veri kuyruğu olarak "\u001E\u0004" ile çevrilir. |
| Macro06 | `6` | 06 Macro karakteri, barkod verisine ilk konumda eklenir. ASC MH10 Veri Tanımlayıcısı ISO 15434 Karakteri, çözülen veri başlığı olarak "[)&gt;\u001E06\u001D" ve çözülen veri kuyruğu olarak "\u001E\u0004" ile çevrilir. |

## Örnekler

Bu örnekler, Macro Characters'ı MicroPdf417 ve DataMatrix içinde nasıl kodlayacağınızı gösterir.

```csharp
[C#]
//ISO 15434 formatında "(10)123ABC(10)123ABC" gibi otomatik tanımlı bir GS1 mesajı oluşturmak için şunlar gerekir:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);
    
//MicroPdf417'yi 05 Macro ile şu dizeyi kodlar: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//MicroPdf417'yi 06 Macro ile şu dizeyi kodlar: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



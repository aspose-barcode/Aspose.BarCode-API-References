---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarcodeSettings özelliği. Tanıma için açıkça belirtilen barkod tiplerini yalnızca döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer tiplerdeki tanınan barkodlar filtrelenir. Varsayılan değer false'tur"
type: docs
weight: 50
url: /tr/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer türlerdeki tanınan barkodlar filtrelenir. Varsayılan değer yanlıştır.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. Varsayılan değer false'dur.

## Örnekler

Bu örnek, tanıma sonuçlarını yalnızca istenen barkod türleriyle sınırlamanın nasıl yapılacağını gösterir.

```csharp
[C#]
//EAN13 barkodu oluştur
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//Yalnızca UPCA barkodlarını tanı (sonuç yok, çünkü kaynak EAN13'tür)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//Uyumlu türleri tanı: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13, UPCA eşdeğeri olarak döndürülecektir)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Ayrıca Bakınız

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)



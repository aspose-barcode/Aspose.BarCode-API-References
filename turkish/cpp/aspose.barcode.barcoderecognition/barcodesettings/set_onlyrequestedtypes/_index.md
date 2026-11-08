---
title: "metot"
linktitle: "set_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " metodu. Tanıma için açıkça belirtilen barkod türlerini yalnızca döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer türlerde tanınan barkodlar filtrelenir. Varsayılan değer C++'da false."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_onlyrequestedtypes/
---
## BarcodeSettings::set_OnlyRequestedTypes method


Yalnızca tanıma için açıkça belirtilen barkod türlerini döndürür. Etkinleştirildiğinde, diğer uyumlu veya eşdeğer türlerdeki tanınan barkodlar filtrelenir. Varsayılan değer yanlıştır.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_OnlyRequestedTypes(bool value)
```

## Açıklamalar


Bu örnek, tanıma sonuçlarını yalnızca istenen barkod türleriyle sınırlamanın nasıl yapılacağını gösterir
```cpp
[C#]
//EAN13 barkodu oluştur
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//yalnızca UPCA barkodlarını tanı (sonuç yok, çünkü kaynak EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//uyumlu türleri tanı: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13, UPCA eşdeğeri olarak döndürülecek)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


Tanıma için açıkça belirtilen barkod türlerini yalnızca döndürür. Varsayılan değer false.
## Ayrıca Bakınız

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

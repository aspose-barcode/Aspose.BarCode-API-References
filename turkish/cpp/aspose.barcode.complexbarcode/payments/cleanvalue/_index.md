---
title: "metot"
linktitle: "CleanValue"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Dize değerini, C++ içinde 2018 İsviçre Ödeme Standartları'na uygun hale getirmek için temizler."
type: docs
weight: 100
url: /tr/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


Bir dize değerini temizleyerek 2018 İsviçre Ödeme Standartları için geçerli hale getirir.

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | System::String | Temizlenecek dize değeri. |
| result | Payments::CleaningResult\& | Temizlenmiş dize ve bayrakla doldurulacak sonuç. |
## Açıklamalar


Desteklenmeyen karakterler (İsviçre Ödeme Standartları 2018, böl. 2.4.1 ve ek D'ye göre) boşluklarla (desteklenmeyen boşluk karakterleri) veya nokta (diğer tüm desteklenmeyen karakterler) değiştirilir. Baş ve son boşluk karakterleri kaldırılır.

0xff'in üzerindeki karakterler tespit edilirse, dize önce iki kod noktasıyla ifade edilen umlaut veya aksanlı harflerin tek bir kod noktasına (mümkünse) birleştirileceği şekilde normalleştirilir, bazıları geçerli hale gelebilir.

Eğer ortaya çıkan dize tamamen boşluk ise, **null** döndürülür.

## Ayrıca Bakınız

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)

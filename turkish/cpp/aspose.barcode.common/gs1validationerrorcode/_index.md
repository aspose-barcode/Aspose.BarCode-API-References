---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'de bir GS1 öğe dizesi, Digital Link URI'si veya değer doğrulama hatasını tanımlar."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Bir GS1 öğe dizesi, Digital Link URI'si veya değer doğrulama hatasını tanımlar

```cpp
enum class GS1ValidationErrorCode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| EmptyElementString | 0 | Sağlanan GS1 öğe dizesi boştur. |
| MissingOpeningParenthesis | 1 | Bir Application Identifier'ı başlatması gereken açılı parantez eksik. |
| MissingClosingParenthesis | 2 | Bir Application Identifier'ın kapanış parantezi yok. |
| InvalidApplicationIdentifier | 3 | Bir Application Identifier iki ila dört ASCII rakamı içermez. |
| UnknownApplicationIdentifier | 4 | Sağlanan Application Identifier, desteklenen GS1 Syntax Dictionary tarafından tanımlanmamıştır. |
| MissingValue | 5 | Bir Application Identifier değersiz olarak bulunuyor. |
| InvalidEscapeSequence | 6 | Bir değer desteklenmeyen bir kaçış dizisi içeriyor. Yalnızca ( desteklenir. |
| ValueTooShort | 7 | Bir değer, Application Identifier için tanımlanan minimum uzunluktan daha kısa. |
| ValueTooLong | 8 | Bir değer, Uygulama Tanımlayıcısı için tanımlanan maksimum uzunluktan daha uzundur. |
| GeçersizKarakter | 9 | Bir değer, bileşeni için izin verilen karakter kümesinin dışındaki bir karakter içerir. |
| GeçersizKontrolToplamı | 10 | Sayısal veya alfabetik bir kontrol toplamı geçersizdir. |
| GeçersizTarih | 11 | Bir tarih bileşeni, Uygulama Tanımlayıcısı için tanımlanan kurallar altında anlamlı bir tarih değildir. |
| GeçersizSaat | 12 | Bir saat bileşeni, izin verilen aralığın dışındadır veya geçersiz bir yapıya sahiptir. |
| GeçersizKodListesiDeğeri | 13 | Bir bileşen değeri, izin verilen kapalı kod listesinde bulunmamaktadır. |
| GeçersizBileşenUzunluğu | 14 | Bir bileşen, bileşene özgü uzunluk yapısını karşılamaz. |
| KırpılmışBileşen | 15 | Sabit uzunluklu bir bileşen, tüm gerekli karakterler mevcut olmadan sona erer. |
| BeklenmeyenVeri | 16 | Uygulama Tanımlayıcısı için tanımlanan tüm bileşenler tüketildikten sonra veri kalır. |
| InvalidValue | 17 | Bir bileşen, daha spesifik bir doğrulama hata kodu olmayan bir içerik kuralını ihlal ediyor. |
| GcpPrefixTooShort | 18 | Bir bileşen, minimum dört basamaklı yapısal GS1 Şirket Öneki'ni içerecek kadar uzun değil. |
| InvalidGcpPrefix | 19 | Yapısal GS1 Şirket Öneki, ASCII rakamı olmayan bir karakter içeriyor. |
| InvalidDigitalLinkUri | 20 | Sağlanan değer, düzgün biçimlendirilmiş mutlak bir GS1 Digital Link URI'si değil. |
| UnsupportedDigitalLinkScheme | 21 | Bir GS1 Digital Link URI, HTTP veya HTTPS dışındaki bir şema kullanıyor. |
| MissingDigitalLinkPrimaryKey | 22 | Bir GS1 Digital Link URI yolu, desteklenen bir birincil anahtar içermiyor. |
| InvalidDigitalLinkPath | 23 | Bir GS1 Digital Link URI yolu, geçerli AI ve değer çiftlerinden oluşmuyor. |
| InvalidDigitalLinkQualifier | 24 | Bir yol Uygulama Tanımlayıcısı, o konumda izin verilen bir niteleyici değil. |
| InvalidDigitalLinkQueryParameter | 25 | Bir GS1 Digital Link sorgu parametresi hatalı biçimlendirilmiş. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Bir Application Identifier, GS1 Digital Link veri özniteliği olarak izin verilmez. |
| InvalidPercentEncoding | 27 | Bir GS1 Digital Link URI bileşeni hatalı yüzde kodlaması içeriyor. |
| MultipleDigitalLinkPrimaryKeys | 28 | GS1 Digital Link birincil anahtarı olarak birden fazla öğe seçilebilir. |
| UnsupportedElementCombination | 29 | Sağlanan GS1 öğeleri kombinasyonu, seçilen semboloji veya kodlama modu tarafından desteklenmiyor. |

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)

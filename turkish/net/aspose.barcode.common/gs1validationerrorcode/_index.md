---
title: "Enum GS1ValidationErrorCode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. GS1 öğe dizesi Digital Link URI'si veya değer doğrulama hatasını tanımlar"
type: docs
weight: 430
url: /tr/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Bir GS1 öğe dizesi, Digital Link URI'si veya değer doğrulama hatasını tanımlar.

```csharp
public enum GS1ValidationErrorCode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| EmptyElementString | `0` | Sağlanan GS1 öğe dizesi boş. |
| MissingOpeningParenthesis | `1` | Bir Application Identifier'ı başlatması gereken açma parantezi eksik. |
| MissingClosingParenthesis | `2` | Bir Application Identifier'ın kapanış parantezi yok. |
| InvalidApplicationIdentifier | `3` | Bir Application Identifier iki ila dört ASCII rakamı içermiyor. |
| UnknownApplicationIdentifier | `4` | Sağlanan Application Identifier, desteklenen GS1 Söz Dizimi Sözlüğü tarafından tanımlanmamış. |
| MissingValue | `5` | Bir Application Identifier değersiz olarak mevcut. |
| InvalidEscapeSequence | `6` | Bir değer desteklenmeyen bir kaçış dizisi içeriyor. Yalnızca \( desteklenir. |
| ValueTooShort | `7` | Bir değer, Application Identifier için tanımlanan minimum uzunluktan daha kısa. |
| ValueTooLong | `8` | Bir değer, Application Identifier için tanımlanan maksimum uzunluktan daha uzun. |
| InvalidCharacter | `9` | Bir değer, bileşeni için izin verilen karakter kümesinin dışındaki bir karakter içeriyor. |
| InvalidChecksum | `10` | Sayısal veya alfabetik kontrol toplamı geçersiz. |
| InvalidDate | `11` | Bir tarih bileşeni, Application Identifier için tanımlanan kurallar altında anlamlı bir tarih değil. |
| InvalidTime | `12` | Bir zaman bileşeni izin verilen aralığın dışında veya geçersiz bir yapıya sahip. |
| InvalidCodeListValue | `13` | Bir bileşen değeri, izin verilen kapalı kod listesinde bulunmuyor. |
| InvalidComponentLength | `14` | Bir bileşen, bileşen‑özel uzunluk yapısını karşılamıyor. |
| TruncatedComponent | `15` | Sabit uzunluklu bir bileşen, tüm gerekli karakterler gelmeden sona eriyor. |
| UnexpectedData | `16` | Application Identifier için tanımlanan tüm bileşenler tüketildikten sonra veri kalıyor. |
| InvalidValue | `17` | Bir bileşen, daha spesifik bir doğrulama hata kodu olmayan bir içerik kuralını ihlal ediyor. |
| GcpPrefixTooShort | `18` | Bir bileşen, minimum dört basamaklı yapısal GS1 Şirket Ön Ekini içerecek kadar kısa. |
| InvalidGcpPrefix | `19` | Yapısal GS1 Şirket Ön eki ASCII rakamı olmayan bir karakter içerir. |
| InvalidDigitalLinkUri | `20` | Sağlanan değer, düzgün biçimlendirilmiş mutlak bir GS1 Digital Link URI değil. |
| UnsupportedDigitalLinkScheme | `21` | Bir GS1 Digital Link URI, HTTP veya HTTPS dışındaki bir şema kullanıyor. |
| MissingDigitalLinkPrimaryKey | `22` | Bir GS1 Digital Link URI yolu, desteklenen bir birincil anahtar içermiyor. |
| InvalidDigitalLinkPath | `23` | Bir GS1 Digital Link URI yolu, geçerli AI ve değer çiftlerinden oluşmuyor. |
| InvalidDigitalLinkQualifier | `24` | Bir yol Uygulama Tanımlayıcısı, o konumda izin verilen bir niteleyici değil. |
| InvalidDigitalLinkQueryParameter | `25` | Bir GS1 Digital Link sorgu parametresi hatalı biçimlendirilmiş. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Bir Uygulama Tanımlayıcısı, GS1 Digital Link veri özniteliği olarak izin verilmez. |
| InvalidPercentEncoding | `27` | Bir GS1 Digital Link URI bileşeni hatalı yüzde kodlaması içeriyor. |
| MultipleDigitalLinkPrimaryKeys | `28` | GS1 Digital Link birincil anahtarı olarak birden fazla öğe seçilebilir. |
| UnsupportedElementCombination | `29` | Sağlanan GS1 öğeleri kombinasyonu, seçilen semboloji veya kodlama modu tarafından desteklenmiyor. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)



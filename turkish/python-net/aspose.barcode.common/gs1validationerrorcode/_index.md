---
title: "GS1ValidationErrorCode"
second_title: "Aspose.Sildes for Python via .NET API Referansı"
description: 
type: docs
url: /tr/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Bir GS1 öğe dizesi, Digital Link URI veya değer doğrulama hatasını tanımlar.

## Members
| Üye adı | Açıklama |
| :- | :- |
| EMPTY_ELEMENT_STRING | Sağlanan GS1 öğe dizesi boş. |
| MISSING_OPENING_PARENTHESIS | Bir Application Identifier'ı başlatması gereken açma parantezi eksik. |
| MISSING_CLOSING_PARENTHESIS | Bir Application Identifier'ın kapanış parantezi yok. |
| INVALID_APPLICATION_IDENTIFIER | Bir Application Identifier iki ila dört ASCII rakamı içermiyor. |
| UNKNOWN_APPLICATION_IDENTIFIER | Sağlanan Application Identifier, desteklenen GS1 Söz Dizimi Sözlüğü tarafından tanımlanmamış. |
| MISSING_VALUE | Bir Application Identifier değersiz olarak mevcut. |
| INVALID_ESCAPE_SEQUENCE | Bir değer desteklenmeyen bir kaçış dizisi içeriyor. Yalnızca \( desteklenir. |
| VALUE_TOO_SHORT | Bir değer, Application Identifier için tanımlanan minimum uzunluktan daha kısa. |
| VALUE_TOO_LONG | Bir değer, Application Identifier için tanımlanan maksimum uzunluktan daha uzun. |
| INVALID_CHARACTER | Bir değer, bileşeni için izin verilen karakter setinin dışındaki bir karakter içeriyor. |
| INVALID_CHECKSUM | Sayısal veya alfabetik bir kontrol toplamı geçersiz. |
| INVALID_DATE | Bir tarih bileşeni, Application Identifier için tanımlanan kurallar altında anlamlı bir tarih değil. |
| INVALID_TIME | Bir zaman bileşeni izin verilen aralığın dışında veya geçersiz bir yapıya sahiptir. |
| INVALID_CODE_LIST_VALUE | Bir bileşen değeri izin verilen kapalı kod listesinde bulunmamaktadır. |
| INVALID_COMPONENT_LENGTH | Bir bileşen, bileşene özgü uzunluk yapısını karşılamamaktadır. |
| TRUNCATED_COMPONENT | Sabit uzunluklu bir bileşen, tüm gerekli karakterler gelmeden sona erer. |
| UNEXPECTED_DATA | Uygulama Tanımlayıcısı için tanımlanan tüm bileşenler tüketildikten sonra veri kalır. |
| INVALID_VALUE | Bir bileşen, daha spesifik bir doğrulama hata kodu olmayan bir içerik kuralını ihlal eder. |
| GCP_PREFIX_TOO_SHORT | Bir bileşen, minimum dört basamaklı yapısal GS1 Şirket Ön Ekini içerecek kadar kısa. |
| INVALID_GCP_PREFIX | Yapısal GS1 Şirket Ön Eki, ASCII rakamı olmayan bir karakter içerir. |
| INVALID_DIGITAL_LINK_URI | Sağlanan değer, düzgün biçimlendirilmiş mutlak bir GS1 Digital Link URI değildir. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Bir GS1 Digital Link URI, HTTP veya HTTPS dışındaki bir şema kullanır. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Bir GS1 Digital Link URI yolu, desteklenen bir birincil anahtar içermez. |
| INVALID_DIGITAL_LINK_PATH | Bir GS1 Digital Link URI yolu, geçerli AI ve değer çiftlerinden oluşmaz. |
| INVALID_DIGITAL_LINK_QUALIFIER | Bir yol Uygulama Tanımlayıcısı, o konumda izin verilen bir niteleyici değildir. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Bir GS1 Digital Link sorgu parametresi hatalıdır. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Bir Application Identifier, GS1 Digital Link veri özniteliği olarak izin verilmez. |
| INVALID_PERCENT_ENCODING | Bir GS1 Digital Link URI bileşeni hatalı yüzde kodlaması içerir. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Birden fazla öğe, GS1 Digital Link birincil anahtarı olarak seçilebilir. |
| UNSUPPORTED_ELEMENT_COMBINATION | Sağlanan GS1 öğeleri kombinasyonu, seçilen semboloji veya kodlama modu tarafından desteklenmez. |

### Ayrıca Bakınız

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)


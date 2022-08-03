---
title: Pdf417Parameters
second_title: Aspose.BarCode for .NET API Referansı
description: PDF417 parametreleri. PDF417 MacroPDF417 ve MicroPDF417 parametrelerini içerir. MacroPDF417 iki alan gerektirir Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. MicroPDF417 Yapılandırılmış Ekleme modunda MacroPDF417 moduyla aynı iki alan gerektirir Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.
type: docs
weight: 860
url: /tr/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 parametreleri. PDF417, MacroPDF417 ve MicroPDF417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. MicroPDF417 Yapılandırılmış Ekleme modunda (MacroPDF417 moduyla aynı) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.

```csharp
public class Pdf417Parameters
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio) { get; set; } | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [Code128Emulation](../../aspose.barcode.generation/pdf417parameters/code128emulation) { get; set; } | Code 128 öykünmesi için işlev kod sözcüğü. Yalnızca MicroPDF417 için geçerlidir. PDF417 ve MacroPDF417 barkodları için yok sayılır. |
| [CodeTextEncoding](../../aspose.barcode.generation/pdf417parameters/codetextencoding) { get; set; } | Codetext kodlamasını alır veya ayarlar. Varsayılan değer: UTF-8 |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns) { get; set; } | Sütun sayısı. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization) { get; set; } | Okuyucuya, symbol içinde bulunan verileri okuyucu başlatma için programlama olarak yorumlama talimatı vermek için kullanılır. |
| [Pdf417CompactionMode](../../aspose.barcode.generation/pdf417parameters/pdf417compactionmode) { get; set; } | Pdf417 BarCode'un sıkıştırma modunun semboloji türü. Varsayılan değer: Pdf417CompactionMode.Auto. |
| [Pdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417eciencoding) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Barkod okuyucunun ayrıntıları 'ye semboldeki verileri kodlamak için kullanılan referansları anlatmak için kullanılır. Makro PDF417 metin alanları için uygulanmadı. Mevcut uygulama, iyi bilinen tüm karakter kümesi kodlamalarından oluşur. |
| [Pdf417ErrorLevel](../../aspose.barcode.generation/pdf417parameters/pdf417errorlevel) { get; set; } | BarCode'un seviye0'dan seviye8'e kadar değişen seviye BarCode hata düzeltmesinin Pdf417 semboloji türünü alır veya ayarlar, seviye0 hata düzeltme bilgisi olmadığı anlamına gelir, seviye8 daha büyük bir resim anlamına gelen en iyi hata düzeltme anlamına gelir. |
| [Pdf417MacroAddressee](../../aspose.barcode.generation/pdf417parameters/pdf417macroaddressee) { get; set; } | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). MicroPDF417 barkod alıcı adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Pdf417MacroChecksum](../../aspose.barcode.generation/pdf417parameters/pdf417macrochecksum) { get; set; } | MacroPdf417 barkod sağlama toplamı (isteğe bağlı alan). MicroPDF417 barkod sağlama toplamı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Sağlama toplamı alanı, CCITT-16 polinomunu kullanan 16 bitlik (2 bayt) CRC sağlama toplamının değerini içerir. x^16 + x^12 + x^5 + 1 |
| [Pdf417MacroECIEncoding](../../aspose.barcode.generation/pdf417parameters/pdf417macroeciencoding) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Makro PDF417 metin alanları için geçerlidir. |
| [Pdf417MacroFileID](../../aspose.barcode.generation/pdf417parameters/pdf417macrofileid) { get; set; } | MacroPdf417 barkodun dosya kimliği (Zorunlu alan). MicroPDF417 barkodun dosya kimliği (Yapılandırılmış Ekleme modu için gerekli alan) |
| [Pdf417MacroFileName](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilename) { get; set; } | MacroPdf417 barkod dosyası adı (isteğe bağlı alan). MicroPDF417 barkod dosyası adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Pdf417MacroFileSize](../../aspose.barcode.generation/pdf417parameters/pdf417macrofilesize) { get; set; } | MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| [Pdf417MacroSegmentID](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentid) { get; set; } | MacroPdf417 barkodun 0'dan başlayan segment kimliği (Gerekli alan), MacroSegmentsCount - 1. MicroPDF417 barkodun segment kimliği (Yapılandırılmış Ekleme modu için gerekli alan) |
| [Pdf417MacroSegmentsCount](../../aspose.barcode.generation/pdf417parameters/pdf417macrosegmentscount) { get; set; } | MacroPdf417 barkod segmentleri sayısı (isteğe bağlı alan). MicroPDF417 barkod segmentleri sayısı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Pdf417MacroSender](../../aspose.barcode.generation/pdf417parameters/pdf417macrosender) { get; set; } | MacroPdf417 barkod gönderen adı (isteğe bağlı alan). MicroPDF417 barkod gönderen adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Pdf417MacroTimeStamp](../../aspose.barcode.generation/pdf417parameters/pdf417macrotimestamp) { get; set; } | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Pdf417Truncate](../../aspose.barcode.generation/pdf417parameters/pdf417truncate) { get; set; } | BarCode'un Pdf417 semboloji türünün kesilip kesilmeyeceği (alanı azaltmak için). CompactPDF417 olarak da bilinir. Bu modda sağ sıra göstergesi ve sağ durdurma düzeni kaldırılır. |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows) { get; set; } | Satır sayısı. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring)() | Bunun insan tarafından okunabilir bir dize temsilini döndürür[`Pdf417Parameters`](../pdf417parameters) . |

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

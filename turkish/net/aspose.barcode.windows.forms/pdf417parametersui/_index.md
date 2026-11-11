---
title: "Sınıf Pdf417ParametersUI"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI sınıfı. Pdf417Parameters sınıfı için UI sarmalayıcı"
type: docs
weight: 1860
url: /tr/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

UI sarmalayıcı [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) sınıfı için.

```csharp
public class Pdf417ParametersUI
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | Sütun sayısı. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında ayrıntıları bildirmek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | BarCode'un kodlama modunun Pdf417 semboloji türü. Varsayılan değer: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | BarCode'un hata düzeltme seviyesinin Pdf417 semboloji türünü alır veya ayarlar; level0'dan level8'e kadar değişir, level0 hata düzeltme bilgisi yok, level8 en iyi hata düzeltme, bu da daha büyük bir resim anlamına gelir. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini belirten 910 ve 911'i de kodlayabilir. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolü 906, 907, 912, 913, 914, 915 “Bağlantılı” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolleri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro Karakter 05 ve 06 değerleri özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod alıcı adı (isteğe bağlı alan) |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod kontrol toplamı (isteğe bağlı alan) Kontrol toplamı alanı, CCITT-16 polinomu kullanılarak 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Macro PDF417 metin alanları için geçerlidir. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Macro Pdf417 barkodunun dosya kimliğini alır veya ayarlar. MacroPdf417 için kullanılır. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417 barkod dosya adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod dosya adı (isteğe bağlı alan) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Macro Pdf417 barkodunun segment kimliğini alır veya ayarlar; bu kimlik 0'dan başlayıp MacroSegmentsCount - 1'e kadar gider. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Macro Pdf417 barkod segment sayısını alır veya ayarlar. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). MicroPDF417 barkod gönderici adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | Kodlayıcıya segmente Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | Satır sayısı. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | BarCode'un Pdf417 sembol tipi kesilmiş mi (alanı azaltmak için). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | Bu [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) nesnesinin insan tarafından okunabilir dize temsili döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)



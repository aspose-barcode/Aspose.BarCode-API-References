---
title: "Sınıf Pdf417Parameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.Pdf417Parameters sınıfı. PDF417 parametreleri. PDF417 MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir. MacroPDF417, Pdf417MacroFileID ve Pdf417MacroSegmentID adlı iki alanı gerektirir. Diğer tüm alanlar isteğe bağlıdır. Structured Append modundaki MicroPDF417, MacroPDF417 moduna benzer şekilde Pdf417MacroFileID ve Pdf417MacroSegmentID adlı iki alanı gerektirir. Diğer tüm alanlar isteğe bağlıdır."
type: docs
weight: 1570
url: /tr/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 parametreleri. PDF417, MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. Structured Append modundaki MicroPDF417 (MacroPDF417 modu ile aynı) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.

```csharp
public class Pdf417Parameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | Sütun sayısı. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında ayrıntıları bildirmek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama tüm bilinen karakter seti kodlamalarını içerir. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Pdf417 kodlama modunu tanımlar. Varsayılan değer: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | BarCode'un hata düzeltme seviyesinin Pdf417 semboloji türünü alır veya ayarlar; level0'dan level8'e kadar değişir, level0 hata düzeltme bilgisi yok, level8 en iyi hata düzeltme, bu da daha büyük bir resim anlamına gelir. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini belirten 910 ve 911'i de kodlayabilir. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolü 906, 907, 912, 913, 914, 915 “Bağlantılı” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolleri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | Okuyucuya, sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Macro Karakter 05 ve 06 değerleri özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod alıcı adı (isteğe bağlı alan) |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod kontrol toplamı (isteğe bağlı alan) Kontrol toplamı alanı, CCITT-16 polinomu kullanılarak 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1 |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Macro PDF417 metin alanları için geçerlidir. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417 barkodunun dosya kimliği (Gerekli alan). Structured Append modu için MicroPDF417 barkodunun dosya kimliği (Gerekli alan). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417 barkod dosya adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod dosya adı (isteğe bağlı alan) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 dosya boyutu (isteğe bağlı alan). MicroPDF417 dosya boyutu (Yapılandırılmış Ekleme modu için isteğe bağlı alan) Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417 barkodunun segment kimliği (Gerekli alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar. Structured Append modu için MicroPDF417 barkodunun segment kimliği (Gerekli alan). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417 barkod segment sayısı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod segment sayısı (isteğe bağlı alan). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). MicroPDF417 barkod gönderici adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | Kodlayıcıya segmente Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini söylemek için kullanılır. Yalnızca Macro PDF417 için uygulanır. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | Satır sayısı. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | BarCode'un Pdf417 semboloji tipinin kesilip kesilmediği (alanı azaltmak için). CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durdurma deseni kaldırılır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | Bu `Pdf417Parameters` nesnesinin insan tarafından okunabilir bir dize temsilini döndürür. |

## Örnekler

Bu örnekler, GS1MicroPdf417 içinde UCC/EAN-128 bağlanmamış modların nasıl kodlanacağını gösterir.

```csharp
[C#]
//AI 01 (GTIN) ile GS1 UCC/EAN-128 bağlanmamış mod 905'i kodlar.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Herhangi bir AI ile GS1 UCC/EAN-128 bağlanmamış modlar 903, 904'ü kodlar.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



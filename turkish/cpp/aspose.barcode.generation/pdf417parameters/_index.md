---
title: "Aspose::BarCode::Generation::Pdf417Parameters sınıfı"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::Pdf417Parameters sınıfı. PDF417 parametreleri. PDF417, MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. Structured Append modundaki MicroPDF417 (MacroPDF417 moduna eşdeğer) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar C++'da isteğe bağlıdır."
type: docs
weight: 4000
url: /tr/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 parametreleri. PDF417, MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. Structured Append modundaki (MacroPDF417 moduna eşdeğer) MicroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.

```cpp
class Pdf417Parameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [get_Columns](./get_columns/)() const | Sütun sayısı. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında ayrıntı vermek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir. |
| [get_EncodeMode](./get_encodemode/)() const | Pdf417 kodlama modunu tanımlar. Varsayılan değer: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | [BarCode](../../aspose.barcode/) öğesinin hata düzeltme seviyesinin level0'dan level8'e kadar değişen Pdf417 semboloji tipini alır, level0 hata düzeltme bilgisi olmadığını, level8 ise en iyi hata düzeltmeyi ve daha büyük bir resmi ifade eder. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir. |
| [get_IsLinked](./get_islinked/)() const | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Sembolde bulunan verileri okuyucu başlatma programlaması olarak yorumlaması için okuyucuya talimat vermek amacıyla kullanılır. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Karakter 05 ve 06 değerleri özel modlarda daha kompakt kodlama elde etmek için kullanılır. Sadece MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod alıcı adı (isteğe bağlı alan). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod kontrol toplamı (isteğe bağlı alan). Kontrol toplamı alanı, CCITT-16 polinomunu kullanan 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1 |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation Identifiers. Macro PDF417 metin alanları için geçerlidir. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 barkodunun dosya kimliği (Gerekli alan). Structured Append modu için MicroPDF417 barkodunun dosya kimliği (Gerekli alan). |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 barkod dosya adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod dosya adı (isteğe bağlı alan). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 dosya boyutu (isteğe bağlı alan). Structured Append modu için MicroPDF417 dosya boyutu (isteğe bağlı alan). Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 barkodunun segment kimliği (Gerekli alan), 0'dan başlayıp MacroSegmentsCount - 1'e kadar gider. Structured Append modu için MicroPDF417 barkodunun segment kimliği (Gerekli alan). |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 barkod segment sayısı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod segment sayısı (isteğe bağlı alan). |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod gönderici adı (isteğe bağlı alan). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | Kodlayıcıya, segmente Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini belirtmek için kullanılır. Yalnızca Macro PDF417 için uygulanır. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod zaman damgası (isteğe bağlı alan). |
| [get_Rows](./get_rows/)() const | Satır sayısı. |
| [get_Truncate](./get_truncate/)() const | [BarCode](../../aspose.barcode/) öğesinin Pdf417 semboloji tipinin sıkıştırılmış (alanı azaltmak için) olup olmadığını belirler. Ayrıca CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durdurma deseni kaldırılır. |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [set_Columns](./set_columns/)(int32_t) | Sütun sayısı. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında ayrıntı vermek için kullanılır. Macro PDF417 metin alanları için uygulanmaz. Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Pdf417 kodlama modunu tanımlar. Varsayılan değer: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | Pdf417 semboloji tipini [BarCode](../../aspose.barcode/)'in hata düzeltme seviyesi olarak ayarlar; seviye0'dan seviye8'e kadar değişir, seviye0 hata düzeltme bilgisi yok demektir, seviye8 en iyi hata düzeltmeyi sağlar ve bu daha büyük bir resim anlamına gelir. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | Sadece MicroPdf417 ile kullanılabilir ve Code 128 emülasyon modlarını kodlar. İkinci konumdaki FNC1'i 908 ve 909 modlarında kodlayabilir, ayrıca 910 ve 911'i kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir. |
| [set_IsLinked](./set_islinked/)(bool) | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Sembolde bulunan verileri okuyucu başlatma programlaması olarak yorumlaması için okuyucuya talimat vermek amacıyla kullanılır. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Karakter 05 ve 06 değerleri özel modlarda daha kompakt kodlama elde etmek için kullanılır. Sadece MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar. Varsayılan değer: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 barkod alıcı adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod alıcı adı (isteğe bağlı alan). |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod kontrol toplamı (isteğe bağlı alan). Kontrol toplamı alanı, CCITT-16 polinomunu kullanan 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1 |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Macro PDF417 metin alanları için geçerlidir. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 barkodunun dosya kimliği (Gerekli alan). Structured Append modu için MicroPDF417 barkodunun dosya kimliği (Gerekli alan). |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 barkod dosya adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod dosya adı (isteğe bağlı alan). |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 dosya boyutu (isteğe bağlı alan). Structured Append modu için MicroPDF417 dosya boyutu (isteğe bağlı alan). Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 barkodunun segment kimliği (Gerekli alan), 0'dan başlayıp MacroSegmentsCount - 1'e kadar gider. Structured Append modu için MicroPDF417 barkodunun segment kimliği (Gerekli alan). |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 barkod segment sayısı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod segment sayısı (isteğe bağlı alan). |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 barkod gönderici adı (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod gönderici adı (isteğe bağlı alan). |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | Kodlayıcıya, segmente Macro PDF417 Terminator (kod sözcüğü 922) ekleyip eklemeyeceğini belirtmek için kullanılır. Yalnızca Macro PDF417 için uygulanır. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 barkod zaman damgası (isteğe bağlı alan). Structured Append modu için MicroPDF417 barkod zaman damgası (isteğe bağlı alan). |
| [set_Rows](./set_rows/)(int32_t) | Satır sayısı. |
| [set_Truncate](./set_truncate/)(bool) | [BarCode](../../aspose.barcode/) öğesinin Pdf417 semboloji tipinin sıkıştırılmış (alanı azaltmak için) olup olmadığını belirler. Ayrıca CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durdurma deseni kaldırılır. |
| [ToString](./tostring/)() const override | Bu [Pdf417Parameters](./) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnekler, GS1MicroPdf417 içinde UCC/EAN-128 bağlanmamış modların nasıl kodlanacağını gösterir.
```cpp
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

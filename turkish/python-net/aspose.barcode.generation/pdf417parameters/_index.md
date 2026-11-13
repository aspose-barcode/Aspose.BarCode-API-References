---
title: "Pdf417Parameters"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.generation/pdf417parameters/
---

## Pdf417Parameters class

PDF417 parametreleri. PDF417, MacroPDF417, MicroPDF417 ve GS1MicroPdf417 parametrelerini içerir.<br/>            MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.<br/>            Yapılandırılmış Ek modundaki MicroPDF417 (MacroPDF417 modu ile aynı) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır.

Pdf417Parameters türü aşağıdaki üyeleri ortaya çıkar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| encode_mode | Pdf417 kodlama modunu tanımlar. <br/>            Varsayılan değer: Auto. |
| error_level | BarCode'un hata düzeltme seviyesinin Pdf417 semboloji tipini alır veya ayarlar<br/>            seviye0'dan seviye8'e kadar, seviye0 hata düzeltme bilgisi yok demektir,<br/>            seviye8 en iyi hata düzeltmeyi sağlar ve daha büyük bir resim anlamına gelir. |
| truncate | BarCode'un Pdf417 semboloji tipinin kesilmiş olup olmadığını (alanı azaltmak için) belirler. <br/>            CompactPDF417 olarak da bilinir. Bu modda sağ satır göstergesi ve sağ durma deseni kaldırılır. |
| sütunlar | Sütun sayısı. |
| satırlar | Satır sayısı. |
| aspect_ratio | 2D Barkod modülünün Yükseklik/Genişlik oranı. |
| macro_pdf_417_file_id | MacroPdf417 barkodunun dosya kimliği (Gerekli alan).<br/>            MicroPDF417 barkodunun dosya kimliği (Yapılandırılmış Ekleme modu için gerekli alan). |
| macro_pdf_417_segment_id | MacroPdf417 barkodunun segment kimliği (Gerekli alan), 0'dan başlayarak MacroSegmentsCount - 1'e kadar.<br/>            MicroPDF417 barkodunun segment kimliği (Yapılandırılmış Ekleme modu için gerekli alan). |
| macro_pdf_417_segments_count | MacroPdf417 barkod segment sayısı (isteğe bağlı alan).<br/>            MicroPDF417 barkod segment sayısı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). |
| macro_pdf_417_file_name | MacroPdf417 barkod dosya adı (isteğe bağlı alan).<br/>            MicroPDF417 barkod dosya adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). |
| macro_pdf_417_time_stamp | MacroPdf417 barkod zaman damgası (isteğe bağlı alan).<br/>            MicroPDF417 barkod zaman damgası (Yapılandırılmış Ekleme modu için isteğe bağlı alan). |
| macro_pdf_417_sender | MacroPdf417 barkod gönderici adı (isteğe bağlı alan).<br/>            MicroPDF417 barkod gönderici adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). |
| macro_pdf_417_addressee | MacroPdf417 barkod alıcı adı (isteğe bağlı alan).<br/>            MicroPDF417 barkod alıcı adı (Yapılandırılmış Ekleme modu için isteğe bağlı alan). |
| macro_pdf_417_file_size | MacroPdf417 dosya boyutu (isteğe bağlı alan).<br/>            MicroPDF417 dosya boyutu (Yapılandırılmış Ek modu için isteğe bağlı alan)<br/>            Dosya boyutu alanı, tüm kaynak dosyanın bayt cinsinden boyutunu içerir. |
| macro_pdf_417_checksum | MacroPdf417 barkod kontrol toplamı (isteğe bağlı alan).<br/>            MicroPDF417 barkod kontrol toplamı (Yapılandırılmış Ek modu için isteğe bağlı alan)<br/>            Kontrol toplamı alanı, CCITT-16 polinomu kullanılarak 16-bit (2 bayt) CRC kontrol toplamı değerini içerir. x^16 + x^12 + x^5 + 1 |
| eci_encoding | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Barkod okuyucuya semboldeki veriyi kodlamak için kullanılan referanslar hakkında detayları bildirmek için kullanılır<br/>            Macro PDF417 metin alanları için uygulanmaz.<br/>            Mevcut uygulama, tüm bilinen karakter seti kodlamalarını içerir. |
| macro_pdf_417eci_encoding | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Macro PDF417 metin alanları için uygulanır. |
| macro_pdf_417_terminator | Kodlayıcıya segment'e Makro PDF417 Terminatörü (kod sözcüğü 922) ekleyip eklemeyeceğini söylemek için kullanılır. <br/>            Yalnızca Makro PDF417 için uygulanır. |
| is_reader_initialization | Okuyucuya sembol içinde bulunan verileri okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır.<br/>             |
| macro_characters | Makro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır.<br/>            Yalnızca MicroPdf417 ile kullanılabilir ve 916 ve 917 MicroPdf417 modlarını kodlar<br/>            Varsayılan değer: MacroCharacters.None. |
| is_linked | GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar<br/>            GS1MicroPdf417 sembolojisi 906, 907, 912, 913, 914, 915 “Bağlantılı” UCC/EAN-128 modlarını kodlar<br/>            MicroPdf417 ve Pdf417 sembolojileri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili lineer bileşene kodlar |
| is_code_128_emulation | Yalnızca MicroPdf417 ile kullanılabilir ve Code 128 taklit modlarını kodlar<br/>            908 ve 909 ikinci konum modlarında FNC1 kodlayabilir, ayrıca 910 ve 911 kodlayabilir; bu sadece tanınan MicroPdf417'nin Code 128 olarak yorumlanabileceğini gösterir |

### Ayrıca Bakınız

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)


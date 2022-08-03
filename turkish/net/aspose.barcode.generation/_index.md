---
title: Aspose.BarCode.Generation
second_title: Aspose.BarCode for .NET API Referansı
description: Aspose.BarCode.Generation BarCode oluşturma işlevlerinin uygulanması için genel sınıflar içerir.
type: docs
weight: 50
url: /tr/net/aspose.barcode.generation/
---
**Aspose.BarCode.Generation** BarCode oluşturma işlevlerinin uygulanması için genel sınıflar içerir.

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [AustralianPostParameters](./australianpostparameters) | AustralianPost barkod parametreleri. |
| [AztecParameters](./aztecparameters) | Aztek parametreleri. |
| [BarcodeGenerator](./barcodegenerator) | Arka uç barkod görüntüleri oluşturmak için BarcodeGenerator. |
| [BarcodeParameters](./barcodeparameters) | Barkod oluşturma parametreleri. |
| [BaseEncodeType](./baseencodetype) | SymbologyEncodeType. için temel sınıf |
| [BaseGenerationParameters](./basegenerationparameters) | Barkod görüntü oluşturma parametreleri. |
| [BorderParameters](./borderparameters) | Barkod görüntü kenarlığı parametreleri |
| [CaptionParameters](./captionparameters) | Altyazı parametreleri. |
| [CodabarParameters](./codabarparameters) | Codabar parametreleri. |
| [CodablockParameters](./codablockparameters) | Codablock parametreleri. |
| [Code16KParameters](./code16kparameters) | Code16K parametreleri. |
| [CodetextParameters](./codetextparameters) | Kod metni parametreleri. |
| [CouponParameters](./couponparameters) | Kupon parametreleri. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. için kullanılır |
| [DataBarParameters](./databarparameters) | Veri çubuğu parametreleri. |
| [DataMatrixParameters](./datamatrixparameters) | DataMatrix parametreleri. |
| [DotCodeParameters](./dotcodeparameters) | DotCode parametreleri. |
| [EncodeTypes](./encodetypes) | Kodlanacak barkod türünü belirtir. |
| [ExtCodetextBuilder](./extcodetextbuilder) | Genişletilmiş Kod Metni Modunun otomatik kod metni üretimi için yardımcı sınıf |
| [FontUnit](./fontunit) | Yazı tipi yüzü, boyutu ve stil öznitelikleri dahil olmak üzere metin için belirli bir biçimi tanımlar burada boyut Birim değeri özelliğindedir. |
| [GS1CompositeBarParameters](./gs1compositebarparameters) | GS1 Bileşik çubuk parametreleri. |
| [ITFParameters](./itfparameters) | ITF parametreleri. |
| [MaxiCodeParameters](./maxicodeparameters) | MaxiCode parametreleri. |
| [Padding](./padding) | Dolgu parametreleri. |
| [PatchCodeParameters](./patchcodeparameters) | Yama Kodu parametreleri. |
| [Pdf417Parameters](./pdf417parameters) | PDF417 parametreleri. PDF417, MacroPDF417 ve MicroPDF417 parametrelerini içerir. MacroPDF417 iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. MicroPDF417 Yapılandırılmış Ekleme modunda (MacroPDF417 moduyla aynı) iki alan gerektirir: Pdf417MacroFileID ve Pdf417MacroSegmentID. Diğer tüm alanlar isteğe bağlıdır. |
| [PostalParameters](./postalparameters) | Posta parametreleri. Postnet için kullanılır, Planet. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder) | QrEncodeMode'un Genişletilmiş Kod Metni Modu için 2D QR barkodları için genişletilmiş kod metni oluşturucu |
| [QrParameters](./qrparameters) | QR parametreleri. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters) | QR yapılandırılmış ekleme parametreleri. |
| [SupplementParameters](./supplementparameters) | Ek parametreler. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. için kullanılır |
| [SymbologyEncodeType](./symbologyencodetype) | Semboloji kodlama türü. Instance. almak için EncodeTypes'a bakın |
| [Unit](./unit) | Boyut değerini farklı birimlerde belirtir (Piksel, İnç, vb.). |
## numaralandırma

| numaralandırma | Tanım |
| --- | --- |
| [AutoSizeMode](./autosizemode) | Otomatik boyutlandırma modlarının farklı türlerini belirtir. |
| [AztecSymbolMode](./aztecsymbolmode) | Aztek sembol modunu belirtir. |
| [BarcodeClassifications](./barcodeclassifications) | Semboloji sınıflandırması |
| [BarCodeImageFormat](./barcodeimageformat) | Resmin dosya biçimini belirtir. |
| [BorderDashStyle](./borderdashstyle) | Kesikli kenar çizgilerinin stilini belirtir. |
| [CodabarChecksumMode](./codabarchecksummode) | Codabar için sağlama toplamı algoritmasını belirtir |
| [CodabarSymbol](./codabarsymbol) | Codabar barkod belirtiminin başlatma veya durdurma sembolünü belirtir. |
| [Code128Emulation](./code128emulation) | Code 128 öykünmesi için işlev kod sözcükleri. Yalnızca MicroPDF417 için geçerlidir. PDF417 ve MacroPDF417 barkodları için yok sayılır. |
| [CodeLocation](./codelocation) | Kod metni konumu |
| [DataMatrixEccType](./datamatrixecctype) | Kodlanacak ECC türünü belirtin. |
| [DataMatrixEncodeMode](./datamatrixencodemode) | DataMatrix kodlayıcının kodlama modu, varsayılan olarak Auto |
| [ECIEncodings](./eciencodings) | Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Semboldeki verileri kodlamak için kullanılan referanslar hakkında barkod okuyucu ayrıntılarını anlatmak için kullanılır. Mevcut uygulama tüm iyi bilinen karakter seti kodlamalarını içerir. Şu anda sadece QR 2D barkodu için kullanılmaktadır. |
| [EnableChecksum](./enablechecksum) | 1D barkodlar için oluşturma sırasında sağlama toplamını etkinleştirin. |
| [FontMode](./fontmode) | Yazı tipi boyutu modu. |
| [ITF14BorderType](./itf14bordertype) | ITF14 barkodun kenarlık türü |
| [MacroCharacter](./macrocharacter) | Makro Karakterleri 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. 05 Makro craracter, kodu çözülen veri başlığı olarak "[)&gt;\u001E05\u001D" ve kodu çözülen veri fragmanı olarak "\u001E\u0004" olarak çevrilir. 06 Makro craracter, kodu çözülen veri başlığı olarak "[)&gt;\u001E06\u001D" ve kodu çözülen veri fragmanı olarak "\u001E\u0004" olarak çevrilir. |
| [PatchFormat](./patchformat) | PatchCode biçimi. Tek bir PatchCode oluşturmak için PatchOnly'yi seçin. PatchCodes ile border olarak Yama sayfası oluşturmak için sayfa biçimini kullanın |
| [Pdf417CompactionMode](./pdf417compactionmode) | Pdf417 barkod sıkıştırma modu |
| [Pdf417ErrorLevel](./pdf417errorlevel) | pdf417 barkodun hata düzeltme seviyesi, seviye 0'dan seviye 9'a kadar, seviye 0 hata düzeltme olmadığı anlamına gelir, seviye 9 en iyi hata düzeltme anlamına gelir |
| [QREncodeMode](./qrencodemode) | QR barkodları için kodlama modu. Latin sembolleri veya rakamları için CodeTextEncoding = Encoding.UTF8 ve Unicode sembolleri için Utf8BOM ile Auto kullanılması önerilir. |
| [QREncodeType](./qrencodetype) | QR / MicroQR seçici modu. Standart QR sembolleri için ForceQR'ı seçin, MicroQR için Otomatik'i seçin. ForceMicroQR, mümkünse güçlü MicroQR sembol üretimi için kullanılır. |
| [QRErrorLevel](./qrerrorlevel) | Reed-Solomon hata düzeltme düzeyi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. |
| [QRVersion](./qrversion) | QR Kodunun Sürümü. QR kodu için Sürüm1'den Sürüm40'a ve MicroQr için M1'den M4'e. |
| [TextAlignment](./textalignment) | Metin hizalaması. |
| [TwoDComponentType](./twodcomponenttype) | 2B bileşen türü |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

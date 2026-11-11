---
title: "Aspose.BarCode.BarCodeRecognition"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition, 1D/2D barkod tanıma için araçlar içerir."
type: docs
weight: 20
url: /tr/net/aspose.barcode.barcoderecognition/
---
Bu **Aspose.BarCode.BarCodeRecognition**, 1D/2D barkodların tanınması için araçlar içerir.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost kod çözme parametreleri. AustraliaPost sembolojisinin tanınan verileri üzerinde etkisi olan parametreler içerir. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec tanınan barkodun özel verilerini depolar |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Tanınan barkodun genişletilmiş parametrelerini depolar |
| [BarCodeReader](./barcodereader/) | BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsar ve ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir. |
| [BarCodeRecognitionException](./barcoderecognitionexception/) | BarCodeReader tarafından fırlatılan genel istisna, BarCodeException'dan miras alınmıştır |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Tanımlanan barkodun bölgesini ve barkod açısını temsil eder |
| [BarCodeResult](./barcoderesult/) | Tanımlanan barkod verilerini, örneğin [`SingleDecodeType`](../aspose.barcode.barcoderecognition/singledecodetype/) tür, String kodmetni, [`BarCodeRegionParameters`](../aspose.barcode.barcoderecognition/barcoderegionparameters/) bölge ve diğer parametreler olarak depolar |
| [BarcodeSettings](./barcodesettings/) | Ana BarCode kod çözme parametreleri. Tanınan veriler üzerinde etkisi olan parametreler içerir. |
| [BaseDecodeType](./basedecodetype/) | MultiDecodeType ve SingleDecodeType için temel sınıf. |
| [BaseExtendedParameters](./baseextendedparameters/) | Tanımlanan barkodun depolanması için genişletilmiş parametrelerin temel sınıfı |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Tanımlanan barkodun Codabar ek bilgilerini depolar |
| [Code128DataPortion](./code128dataportion/) | Code128 tipindeki barkodun alt tip verilerini içerir |
| [Code128ExtendedParameters](./code128extendedparameters/) | Code128 tanınan barkodun özel verilerini depolar |
| [DataBarExtendedParameters](./databarextendedparameters/) | Tanımlanan barkodun DataBar ek bilgilerini depolar |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | DataMatrix tanınan barkodun özel verilerini depolar |
| [DecodeType](./decodetype/) | Okunacak barkod tipini belirtin. |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | DotCode tanınan barkodun özel verilerini depolar |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Tanımlanan **GS1 Composite Bar** barkodunun özel verilerini depolar |
| [Iso15416Quality](./iso15416quality/) | 1D barkodlar için ISO/IEC 15416 standardına göre hesaplanan barkod kalite derecelerini depolar. |
| [IsoSymbolQuality](./isosymbolquality/) | Barkod sembolü kalite değerlendirme sonuçlarını ISO/IEC standartlarına göre depolar. |
| [LuminanceFrame](./luminanceframe/) | 8 bitlik gri tonlamalı bir görüntü çerçevesini temsil eder. Her piksel, parlaklık değerini içeren bir bayt ile temsil edilir. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Tanımlanan barkodun bir MaxiCode ek bilgisini depolar |
| [MultiDecodeType](./multidecodetype/) | Kompozit çözümleme türü. |
| [OneDExtendedParameters](./onedextendedparameters/) | Ayrı kod metni ve kontrol toplamı gibi 1D tanımlanan barkodun özel verilerini depolar |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Tanımlanan barkodun bir MacroPdf417 meta veri bilgisini depolar |
| [QRExtendedParameters](./qrextendedparameters/) | Tanımlanan barkodun bir QR Structured Append bilgisini depolar |
| [Quadrangle](./quadrangle/) | Bir [`Quadrangle`](../aspose.barcode.barcoderecognition/quadrangle/) bölgesini temsil eden dört Nokta kümesini depolar. |
| [QualitySettings](./qualitysettings/) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i gömülü ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxQuality veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir. |
| [RecognitionAbortedException](./recognitionabortedexception/) | BarCodeReader ile tanıma sırasında zaman aşımı aşıldığında atılan tanıma iptal istisnasını temsil eder. |
| [SingleDecodeType](./singledecodetype/) | Tek çözümleme türü. Örneği almak için decode type'a bakın. |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözme için genel arayüz. Uygulama kullanıcı tarafından sağlanmalıdır. |
## Sınıflandırma

| Sınıflandırma | Açıklama |
| --- | --- |
| [BarCodeConfidence](./barcodeconfidence/) | Tanıma güven düzeyini içerir |
| [BarcodeQualityMode](./barcodequalitymode/) | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir. |
| [ChecksumValidation](./checksumvalidation/) | 1D ve Posta barkodları için tanıma sırasında kontrol toplamı doğrulamasını etkinleştir. |
| [Code128SubType](./code128subtype/) | Code128 alt kümesinin türlerini içerir |
| [ComplexBackgroundMode](./complexbackgroundmode/) | Renkli görüntülerde renkli barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod. |
| [DeconvolutionMode](./deconvolutionmode/) | Dekonvolüsyon (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri yükleyebilen bir işlevtir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir. |
| [InverseImageMode](./inverseimagemode/) | Renkleri (parlaklığı) ters çevrilmiş görüntülerde barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod. |
| [XDimensionMode](./xdimensionmode/) | Barkodun en küçük öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu. |



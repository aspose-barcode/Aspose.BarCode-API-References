---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Bu paket, 1D/2D barkod tanıma araçları içerir."
type: docs
weight: 11
url: /tr/androidjava/com.aspose.barcode.barcoderecognition/
---

Bu paket, 1D/2D barkod tanıma araçları içerir.


## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost kod çözme parametreleri. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec tanınan barkodun özel verilerini depolar |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Tanınan barkodun genişletilmiş parametrelerini depolar |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader, bir veya birden fazla barkod içerebilecek bir görüntüyü kapsüller, ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader tarafından atılan genel istisna, BarCodeException'dan miras alınmıştır |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Tanınan barkodun bölgesini ve barkod açısını temsil eder |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | SingleDecodeType türü, string kodmetni, BarCodeRegionParameters bölgesi ve diğer parametreler gibi tanınan barkod verilerini depolar |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Ana BarCode kod çözme parametreleri. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barkod algılayıcı ayarları. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType ve SingleDecodeType için temel sınıf. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Tanınan barkodun depolanması için genişletilmiş parametrelerin temel sınıfı |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Tanınan barkodun ek Codabar bilgilerini depolar |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 tipindeki barkodun alt tip verilerini içerir |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Code128 tanınan barkodun özel verilerini depolar |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Tanımlanan barkodun DataBar ek bilgilerini depolar BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Tanımlanan DataMatrix barkodunun özel verilerini depolar |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Okunacak barkod tipini belirtin. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Tanımlanan DotCode barkodunun özel verilerini depolar |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Tanımlanan **GS1 Composite Bar** barkodunun özel verilerini depolar |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Tanımlanan barkodun MaxiCode ek bilgilerini depolar |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Bileşik çözümleme tipi. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Tanımlanan 1D barkodunun ayrı kod metni ve kontrol toplamı gibi özel verilerini depolar |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Tanımlanan barkodun MacroPdf417 meta veri bilgilerini depolar |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımaya olanak tanır |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Tanımlanan barkodun QR Structured Append bilgisini depolar |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Dört adet Point'i depolar; bu Point'ler bir Quadrangle bölgesini temsil eder. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | BarCodeReader ile tanıma sırasında zaman aşımını aşınca atılan tanıma iptal istisnasını temsil eder. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tek çözümleme tipi. |

## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | AustraliaPost sembolojisinde kullanılan Müşteri Bilgi Alanı kod çözümü için genel arayüz. |

## Sıralamalar

| Enum | Açıklama |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Tanıma güven düzeyini içerir |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Code128 alt kümesinin tiplerini içerir |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost BarCode için müşteri bilgilerinin yorumlama tipini (C\_TABLE veya N\_TABLE) tanımlar |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Ölçeklenmiş görüntünün boyutunu belirtin |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

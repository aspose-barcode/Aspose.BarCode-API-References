---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode for Java API Referansı"
description: "Bu paket, 1D/2D barkod tanıma araçları içerir."
type: docs
weight: 12
url: /tr/java/com.aspose.barcode.barcoderecognition/
---

Bu paket, 1D/2D barkod tanıma araçları içerir.


## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost kod çözme parametreleri. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec tanınan barkodun özel verilerini saklar |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Tanımlanan barkodun genişletilmiş parametrelerini saklar |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader, bir veya birkaç barkod içerebilecek bir görüntüyü kapsüller, ardından barkodları tespit etmek için ReadBarCodes işlemini gerçekleştirebilir. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader tarafından atılan genel istisna, BarCodeException'dan miras alınmıştır. |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Tanımlanan barkodun bölgesini ve barkod açısını temsil eder. |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Tanımlanan barkod verilerini, örneğin SingleDecodeType türü, string codetext, BarCodeRegionParameters bölgesi ve diğer parametreleri saklar |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Ana BarCode kod çözme parametreleri. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Barkod algılayıcı ayarları. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType ve SingleDecodeType için temel sınıf. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Tanımlanan barkodun saklanması için genişletilmiş parametrelerin temel sınıfı |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Tanımlanan barkodun Codabar ek bilgilerini depolar |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 tipindeki barkod için alt tip verilerini içerir |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Tanımlanan Code128 barkodunun özel verilerini depolar |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Tanımlanan barkodun DataBar ek bilgilerini depolar BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Tanımlanan DataMatrix barkodunun özel verilerini depolar |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Okunacak barkod tipini belirtin. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Tanımlanan DotCode barkodunun özel verilerini depolar |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Tanımlanan  **GS1 Composite Bar**  barkodunun özel verilerini depolar |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Tanımlanan barkodun MaxiCode ek bilgilerini depolar |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Bileşik çözümleme türü. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Tanımlanan 1D barkodunun ayrı kod metni ve kontrol toplamı gibi özel verilerini depolar |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Tanımlanan barkodun MacroPdf417 meta veri bilgilerini depolar |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings, çok iş parçacıklı performans artışıyla barkodları tanımaya olanak tanır |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Tanımlanan barkodun QR Structured Append bilgilerini depolar |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Dört  Point  öğesinden oluşan bir küme depolar; bu öğeler bir  Quadrangle  bölgeyi temsil eder. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmaya izin verir. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | BarCodeReader ile tanıma sırasında zaman aşımı aşıldığında atılan tanıma iptal istisnasını temsil eder. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tek çözümleme türü. |

## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | AustraliaPost sembolojisinde kullanılan Customer Information Field kod çözme için genel arayüz. |

## Enumlar

| Enum | Açıklama |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Tanıma güven düzeyini içerir |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Code128 alt kümesinin türlerini içerir. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost BarCode için müşteri bilgilerinin yorumlama türünü (C\_TABLE veya N\_TABLE) tanımlar. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

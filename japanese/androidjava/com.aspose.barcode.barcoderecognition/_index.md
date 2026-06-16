---
title: com.aspose.barcode.barcoderecognition
second_title: Aspose.BarCode for Android via Java API Reference
description: This package contains tools for 1D/2D barcode recognition.
type: docs
weight: 11
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/
---

This package contains tools for 1D/2D barcode recognition.


## Classes

| Class | Description |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPost のデコードパラメータ。 |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec 認識バーコードの特殊データを保存します |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | 認識信頼度レベルを含みます |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | 認識されたバーコードの拡張パラメータを保存します |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader は、1 つまたは複数のバーコードを含む可能性のある画像をカプセル化し、ReadBarCodes 操作を実行してバーコードを検出できます。 |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReader がスローする一般的な例外で、BarCodeException から継承されます |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | 認識されたバーコードの領域とバーコードの角度を表します |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | SingleDecodeType 型、string codetext、BarCodeRegionParameters region などの認識バーコードデータを保存します |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | 主な BarCode デコードパラメータです。 |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | バーコード検出器の設定。 |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType と SingleDecodeType の基底クラスです。 |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | 認識されたバーコードの保存用拡張パラメータの基本クラスです |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | 認識されたバーコードの Codabar 追加情報を保存します |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128 タイプのバーコードのサブタイプデータを含みます |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Stores special data of Code128 recognized barcode |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Contains types of Code128 subset |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Stores a DataBar additional information of recognized barcode BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Stores special data of DataMatrix recognized barcode |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Specify the type of barcode to read. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Stores special data of DotCode recognized barcode |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Stores special data of  **GS1 Composite Bar**  recognized barcode |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Stores a MaxiCode additional information of recognized barcode |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Composite decode type. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Composite decode type. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Stores special data of 1D recognized barcode like separate codetext and checksum |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Stores a MacroPdf417 metadata information of recognized barcode |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings allow to recognize barcodes with multi-threaded increasing of performance |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Stores a QR Structured Append information of recognized barcode |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Stores a set of four  Point s that represent a  Quadrangle  region. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings allows to configure recognition quality and speed manually. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Represents recognition abort exception which is thrown in timeout exceeding during recognition with BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Single decode type. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## インターフェイス

| インターフェイス | Description |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Public interface for Customer Information Field decoding which is used in AustraliaPost symbology. |

## 列挙型

| 列挙型 | Description |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Defines the interpreting type(C\_TABLE or N\_TABLE) of customer information for AustralianPost BarCode. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Specify the size of scaled image |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

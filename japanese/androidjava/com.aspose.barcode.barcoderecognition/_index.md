---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "このパッケージには、1D/2D バーコード認識用のツールが含まれています。"
type: docs
weight: 11
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/
---

このパッケージには、1D/2D バーコード認識用のツールが含まれています。


## クラス

| クラス | 説明 |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | AustraliaPostのデコードパラメータです。 |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Aztec認識バーコードの特別なデータを保存します |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | 認識されたバーコードの拡張パラメータを保存します |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReaderは、1つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するためにReadBarCodes操作を実行できます。 |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | BarCodeReaderからスローされる一般的な例外で、BarCodeExceptionから継承されます。 |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | 認識されたバーコードの領域とバーコードの角度を表します |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | SingleDecodeType 型、string codetext、BarCodeRegionParameters region などの認識されたバーコードデータを保存します |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | 主要なBarCodeデコードパラメータです。 |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | バーコード検出器の設定です。 |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | MultiDecodeType と SingleDecodeType の基底クラスです。 |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | 認識されたバーコードの保存用拡張パラメータの基本クラスです |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | 認識されたバーコードのCodabar追加情報を保存します |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Code128タイプのバーコードのサブタイプデータを含みます |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Code128認識バーコードの特別なデータを保存します |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | 認識されたバーコードの DataBar 追加情報を保存します BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | 認識された DataMatrix バーコードの特別なデータを保存します |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | 読み取るバーコードのタイプを指定します。 |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | 認識された DotCode バーコードの特別なデータを保存します |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | 認識された  **GS1 Composite Bar**  バーコードの特別なデータを保存します |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | 認識されたバーコードの MaxiCode 追加情報を保存します |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | 複合デコードタイプです。 |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) |  |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | 認識された 1D バーコードの、コードテキストやチェックサムなどの特別なデータを保存します |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | 認識されたバーコードの MacroPdf417 メタデータ情報を保存します |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings は、マルチスレッド化によるパフォーマンス向上でバーコードを認識できるようにします |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 認識されたバーコードの QR Structured Append 情報を保存します |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | 四つの Point が Quadrangle 領域を表すセットを保存します |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings は、認識の品質と速度を手動で構成できるようにします。 |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | BarCodeReader での認識中にタイムアウトが超過した際にスローされる、認識中止例外を表します。 |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | 単一デコードタイプです。 |

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | AustraliaPost のシンボルで使用される Customer Information Field デコード用の公開インターフェイスです。 |

## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | 認識の信頼度レベルを含みます |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Code128 サブセットのタイプを含みます。 |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | AustralianPost バーコードの顧客情報の解釈タイプ（C_TABLE または N_TABLE）を定義します。 |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | スケーリングされた画像のサイズを指定します |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

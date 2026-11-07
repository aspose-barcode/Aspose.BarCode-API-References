---
title: "Aspose::BarCode::BarCodeRecognition 名前空間"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++で Aspose::BarCode::BarCodeRecognition 名前空間を使用する方法。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode.barcoderecognition/
---



## クラス

| クラス | 説明 |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | AustraliaPost シンボルで使用される顧客情報フィールドデコードの公開インターフェイス。実装はユーザーが提供する必要があります。 |
| [AustraliaPostSettings](./australiapostsettings/) | AustraliaPost デコードパラメーター。AustraliaPost シンボルの認識データに影響を与えるパラメーターを含みます。 |
| [AztecExtendedParameters](./aztecextendedparameters/) | Aztec 認識バーコードの特殊データを格納します |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | 認識されたバーコードの拡張パラメーターを格納します |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) は、1つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。 |
| [BarCodeRegionParameters](./barcoderegionparameters/) | 認識されたバーコードの領域とバーコードの角度を表します |
| [BarCodeResult](./barcoderesult/) | 認識されたバーコードデータを格納します。たとえば [SingleDecodeType](./singledecodetype/) 型、**System::String** codetext、[BarCodeRegionParameters](./barcoderegionparameters/) 領域、その他のパラメーターです。 |
| [BarcodeSettings](./barcodesettings/) | メインの [BarCode](../aspose.barcode/) デコードパラメーター。認識データに影響を与えるパラメーターを含みます。 |
| [BaseDecodeType](./basedecodetype/) | [MultiDecodeType](./multidecodetype/) と [SingleDecodeType](./singledecodetype/) の基底クラスです。 |
| [BaseExtendedParameters](./baseextendedparameters/) | 認識されたバーコードの格納用拡張パラメーターの基本クラス |
| [CodabarExtendedParameters](./codabarextendedparameters/) | 認識されたバーコードの Codabar 追加情報を格納します |
| [Code128DataPortion](./code128dataportion/) | Code128 タイプのバーコードのサブタイプデータを含みます |
| [Code128ExtendedParameters](./code128extendedparameters/) | Code128 認識バーコードの特殊データを格納します |
| [DataBarExtendedParameters](./databarextendedparameters/) | 認識されたバーコードの DataBar 追加情報を格納します |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | 認識された [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) バーコードの特殊データを格納します |
| [DecodeType](./decodetype/) | 読み取るバーコードのタイプを指定します。 |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | [BarCodeReader](./barcodereader/) がスローする一般的な例外で、BarCodeException から継承されています。 |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | [BarCodeReader](./barcodereader/) による認識中にタイムアウトが超過した際にスローされる認識中止例外を表します。 |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | DotCode 認識バーコードの特殊データを格納します |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | 認識された **GS1 Composite Bar** の特殊データを格納します |
| [Iso15416Quality](./iso15416quality/) | ISO/IEC 15416 標準に基づいて計算された 1D バーコードのバーコード品質等級を保存します。 |
| [IsoSymbolQuality](./isosymbolquality/) | ISO/IEC 標準に従ってバーコードシンボルの品質評価結果を保存します。 |
| [LuminanceFrame](./luminanceframe/) | 8 ビットのグレースケール画像フレームを表します。各ピクセルは、輝度値を含む 1 バイトで表現されます。 |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | 認識されたバーコードの MaxiCode 追加情報を保存します。 |
| [MultiDecodeType](./multidecodetype/) | 複合デコードタイプです。 |
| [OneDExtendedParameters](./onedextendedparameters/) | 認識された 1D バーコードの、個別のコードテキストやチェックサムなどの特殊データを保存します。 |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | 認識されたバーコードの MacroPdf417 メタデータ情報を保存します。 |
| [QRExtendedParameters](./qrextendedparameters/) | 認識されたバーコードの [QR](../aspose.barcode.barcoderecognition.qr/) 構造化付加情報を保存します。 |
| [Quadrangle](./quadrangle/) | 4 つの [Point](../)s を保存し、[Quadrangle](./quadrangle/) 領域を表します。 |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) は、認識品質と速度を手動で構成できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxQuality）を使用して [QualitySettings](./qualitysettings/) をすばやく設定することも、個別のオプションを手動で構成することもできます。[QualitySettings](./qualitysettings/) のデフォルト値は NormalQuality です。 |
| [SingleDecodeType](./singledecodetype/) | 単一デコードタイプです。インスタンスを取得するには decode type を参照してください。 |
## Enums

| 列挙型 | 説明 |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Code128 サブセットのタイプを含みます。 |
| [BarCodeConfidence](./barcodeconfidence/) | 認識の信頼度レベルを含みます。 |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| 型定義 | 説明 |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |

---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings クラス"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings クラス。QualitySettings は認識の品質と速度を手動で構成できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxQuality）で簡単に設定できるほか、個別のオプションを手動で構成することも可能です。C++ における QualitySettings のデフォルト値は NormalQuality です。"
type: docs
weight: 3100
url: /ja/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | エンジンがチェックサムまたは値が正しくないバーコードを認識できるようにします。このモードは、テキストが正しくない損傷したバーコードの認識に使用できます。 |
| [get_BarcodeQuality](./get_barcodequality/)() const | 選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識が遅くなります。 |
| [get_ComplexBackground](./get_complexbackground/)() const | カラー画像上のカラーバーコードの追加認識を有効または無効にするモードです。 |
| [get_Deconvolution](./get_deconvolution/)() const | 画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。デコンボリューションは、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。 |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance 認識品質プリセット。このモードでは高品質のバーコードが適切に認識されます。 |
| static [get_HighQuality](./get_highquality/)() | HighQuality 認識品質プリセット。このプリセットは低品質のバーコード向けに開発され、極度に損傷したバーコードの検出を可能にします。 |
| [get_InverseImage](./get_inverseimage/)() const | 色が反転した（輝度）画像上のバーコードの追加認識を有効または無効にするモードです。 |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality 認識品質プリセット。このプリセットは、可能なすべてのバーコード、さらには誤ったバーコードまで認識できるように開発されています。 |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル単位）。 |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。 |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) モードは、バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）を設定します。 |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | エンジンがチェックサムまたは値が正しくないバーコードを認識できるようにします。このモードは、テキストが正しくない損傷したバーコードの認識に使用できます。 |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | 選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドを必要とし、認識が遅くなります。 |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | カラー画像上のカラーバーコードの追加認識を有効または無効にするモードです。 |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | 画像劣化のレベルを定義するデコンボリューション（画像復元）モードです。デコンボリューションは、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。画像を劣化させる関数を検出できないため、シャープや数学的形態学など、よく知られた関数をチェックする必要があります。 |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | 色が反転した（輝度）画像上のバーコードの追加認識を有効または無効にするモードです。 |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル単位）。 |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) モードは、バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）を設定します。 |
## 備考


このサンプルは、[QualitySettings](./) と [BarCodeReader](../barcodereader/) の使用方法を示しています。
```cpp
[C#]
//HighPerformance 認識モードを設定する
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality 認識モードを設定する
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//小サイズのバーコード用に HighPerformance 認識モードを設定する
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//低品質のバーコード用に HighPerformance 認識モードを設定する
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

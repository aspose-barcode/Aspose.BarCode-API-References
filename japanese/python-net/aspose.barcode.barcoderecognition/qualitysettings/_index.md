---
title: "QualitySettings"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettingsは認識品質と速度を手動で構成できるようにします。<br/>            組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxQuality）でQualitySettingsをすばやく設定することも、個別のオプションを手動で構成することもできます。<br/>            QualitySettingsのデフォルト値はNormalQualityです。

QualitySettings 型は次のメンバーを公開します：
## プロパティ
| 名前 | 説明 |
| :- | :- |
| high_performance | HighPerformance 認識品質プリセット。このモードでは高品質のバーコードがうまく認識されます。 |
| normal_quality | NormalQuality 認識品質プリセット。ほとんどのバーコードに適しています。 |
| high_quality | HighQuality 認識品質プリセット。このプリセットは低品質のバーコード用に開発されました。高度に損傷したバーコードの検出を可能にします。 |
| max_quality | MaxQuality 認識品質プリセット。このプリセットは、正しくないバーコードも含め、可能なすべてのバーコードを認識できるように開発されました。 |
| x_dimension | バーコードの最小要素（マトリックスセルまたはバー）のサイズ（1 から無限大まで）を設定する認識モード。 |
| minimal_x_dimension | UseMinimalXDimension と共に使用される XDimension の最小サイズ（ピクセル）。 |
| barcode_quality | 選択された品質でバーコード要素を認識するメソッドを有効にするモード。品質が低いバーコード要素は、より多くの高度な手法が必要となり、認識が遅くなります。 |
| deconvolution | デコンボリューション（画像復元）モードは、画像劣化のレベルを定義します。もともとデコンボリューションは、カメラで画像を取得する際にぼかしなどの自然な関数によって劣化（畳み込み）した画像を復元できる機能です。<br/>            画像を破損させる関数を検出できないため、<br/>            シャープや数学的形態学など、最もよく知られた関数をチェックする必要があります。 |
| inverse_image | 色が反転した画像（輝度）上のバーコードの追加認識を有効または無効にするモード。 |
| complex_background | カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。 |
| allow_incorrect_barcodes | エンジンがチェックサムや値が正しくないバーコードを認識できるようにします。このモードは、テキストが正しくない損傷したバーコードの認識にも使用できます。 |

### 関連項目

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)


---
title: "BarCodeReader"
second_title: "Aspose.BarCode for Python via .NET API リファレンス"
description: 
type: docs
url: /ja/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader は、1つまたは複数のバーコードを含む可能性のある画像をカプセル化し、バーコードを検出するために ReadBarCodes 操作を実行できます。

BarCodeReader 型は以下のメンバーを公開します：
## コンストラクター
| 名前 | 説明 |
| :- | :- |
| BarCodeReader() | デフォルト値で [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) クラスの新しいインスタンスを初期化します。<br/>            ReadBarCodes() メソッドを呼び出す前に画像を設定（SetBitmapImage()）する必要があります。 |
| BarCodeReader(image) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, area, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, area, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, areas, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(image, areas, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(filename) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(filename, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(filename, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(stream) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(stream, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(stream, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, areas, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, areas, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, area, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, area, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, type) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame, decode_types) | BarCodeReader クラスの新しいインスタンスを初期化します |
| BarCodeReader(frame) | BarCodeReader クラスの新しいインスタンスを初期化します |
## プロパティ
| 名前 | 説明 |
| :- | :- |
| processor_settings | プロセッサ コアの使用設定を取得します。 |
| timeout | 認識プロセスのタイムアウト（ミリ秒）を取得または設定します。 |
| found_bar_codes | 認識された [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) の配列を取得します |
| found_count | 認識されたバーコードの数を取得します |
| quality_settings | QualitySettings は認識の品質と速度を手動で構成できるようにします。<br/>            組み込みのプリセット（HighPerformance、NormalQuality、<br/>            HighQuality、MaxBarCodes）を使用して QualitySettings をすばやく設定できます。または、個別のオプションを手動で構成することもできます。<br/>            QualitySettings のデフォルト値は NormalQuality です。 |
| barcode_settings | 主要な BarCode デコードパラメーター。認識されたデータに影響を与えるパラメーターを含みます。 |
| bar_code_read_type | 認識に使用されるバーコードデコードタイプを取得または設定します。<br/>            呼び出す前に設定する必要があります [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/)。 |
## メソッド
| 名前 | 説明 |
| :- | :- |
| set_bar_code_image(value) | 認識用にビットマップ画像を設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(value, areas) | 認識用にビットマップ画像と領域を設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(value, area) | 認識用にビットマップ画像と領域を設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(filename) | 認識用に画像ファイルを設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(stream) | 認識用に画像ストリームを設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(frame, area) | 認識用に輝度フレームと領域を設定します。 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(frame, areas) | 認識用に輝度フレームと領域を設定します。 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) メソッドの前に呼び出す必要があります。 |
| set_bar_code_image(frame) | 認識用に輝度フレームと領域を設定します。 [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) メソッドの前に呼び出す必要があります。 |
| export_to_xml(xml_file) | 指定された XML ファイルに BarCode プロパティをエクスポートします |
| export_to_xml(xml_stream) | 指定された XML ストリームに BarCode プロパティをエクスポートします |
| import_from_xml(xml_file) | 指定された XML ファイルから BarCode プロパティをインポートし、現在の BarCodeReader インスタンスに適用します。 |
| import_from_xml(xml_stream) | 指定された XML ストリームから BarCode プロパティをインポートし、現在の BarCodeReader インスタンスに適用します。 |
| abort() | この関数は別スレッドから現在の認識セッションの終了を要求します。Abort はブロックできないメソッドで、呼び出した直後に制御が戻ります。 <br/>            認識処理が長時間にわたる場合にこのメソッドを使用すべきです。 |
| read_bar_codes() | 画像から [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s を読み取ります。 |
| set_bar_code_read_type(barcode_types) | 認識用に [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) type 配列を設定します。 <br/>            ReadBarCodes() メソッドの前に呼び出す必要があります。 |

### 関連項目

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)


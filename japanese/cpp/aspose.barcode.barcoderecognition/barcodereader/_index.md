---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader クラス"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader クラス。BarCodeReader は、1 つまたは複数のバーコードを含む可能性のある画像をカプセル化し、C++ でバーコードを検出するために ReadBarCodes 操作を実行できます。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Abort](./abort/)() | この関数は、別スレッドから現在の認識セッションの終了を要求します。Abort はブロック解除できないメソッドで、呼び出し直後に制御を返します。認識プロセスが長すぎる場合にこのメソッドを使用すべきです。 |
| [BarCodeReader](./barcodereader/)() | デフォルト値で [BarCodeReader](./) クラスの新しいインスタンスを初期化します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に画像（SetBitmapImage()）を設定する必要があります。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 画像から [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::String) | ファイルから [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | 輝度フレームから [BarCodeReader](./) クラスの新しいインスタンスを初期化します。 |
| [Dispose](./dispose/)() override | リソースを解放する |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) のプロパティを指定された XML ファイルにエクスポートします |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) のプロパティを指定された XML ストリームにエクスポートします |
| [get_BarCodeReadType](./get_barcodereadtype/)() | 認識に使用されるバーコードデコードタイプを取得します。[ReadBarCodes](./readbarcodes/) を呼び出す前に設定する必要があります。 |
| [get_BarcodeSettings](./get_barcodesettings/)() | 主要な [BarCode](../../aspose.barcode/) デコードパラメータ。認識されたデータに影響を与えるパラメータを含みます。 |
| [get_FoundBarCodes](./get_foundbarcodes/)() | 認識された [BarCodeResult](../barcoderesult/) の配列を取得します |
| [get_FoundCount](./get_foundcount/)() | 認識されたバーコードの数を取得します |
| static [get_ProcessorSettings](./get_processorsettings/)() | プロセッサコアの使用設定を取得します。 |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) は認識の品質と速度を手動で設定できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用して [QualitySettings](../qualitysettings/) をすばやく設定することも、個別のオプションを手動で構成することもできます。[QualitySettings](../qualitysettings/) のデフォルト値は NormalQuality です。 |
| [get_Timeout](./get_timeout/)() | 認識プロセスのタイムアウト（ミリ秒）を取得します。 |
| static [ImportFromXml](./importfromxml/)(System::String) | 指定された XML ファイルから [BarCode](../../aspose.barcode/) のプロパティをインポートし、現在の [BarCodeReader](./) インスタンスに適用します。 |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 指定された XML ストリームから [BarCode](../../aspose.barcode/) のプロパティをインポートし、現在の [BarCodeReader](./) インスタンスに適用します。 |
| [ReadBarCodes](./readbarcodes/)() | 画像から [BarCodeResult](../barcoderesult/) を読み取ります。 |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | 認識に使用されるバーコードデコードタイプを設定します。[ReadBarCodes](./readbarcodes/) を呼び出す前に設定する必要があります。 |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) は認識の品質と速度を手動で設定できるようにします。組み込みのプリセット（HighPerformance、NormalQuality、HighQuality、MaxBarCodes）を使用して [QualitySettings](../qualitysettings/) をすばやく設定することも、個別のオプションを手動で構成することもできます。[QualitySettings](../qualitysettings/) のデフォルト値は NormalQuality です。 |
| [set_Timeout](./set_timeout/)(int32_t) | 認識プロセスのタイムアウト（ミリ秒）を設定します。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | 認識用にビットマップ画像を設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 認識用にビットマップ画像と領域を設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | 認識用にビットマップ画像と領域を設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | 認識用に画像ファイルを設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | 認識用に画像ストリームを設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | 認識用に輝度フレームと領域を設定します。[ReadBarCodes](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | 認識用に輝度フレームと複数の領域を設定します。[ReadBarCodes](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | 認識用に輝度フレームを設定します。[ReadBarCodes](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [SingleDecodeType](../singledecodetype/) のタイプ配列を認識用に設定します。[ReadBarCodes()](./readbarcodes/) メソッドを呼び出す前に実行する必要があります。 |
## 備考


このサンプルは Code39 と Code128 バーコードの検出方法を示しています。
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)

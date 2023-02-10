---
title: BarCodeReader
second_title: Aspose.BarCode for.NETAPIリファレンス
description: BarCodeReader は1 つまたは複数のバーコードを含む画像をカプセル化しReadBarCodes 操作を実行してバーコードを検出できます
type: docs
weight: 60
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader は、1 つまたは複数のバーコードを含む画像をカプセル化し、ReadBarCodes 操作を実行してバーコードを検出できます。

```csharp
public class BarCodeReader : Component
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | の新しいインスタンスを初期化します`BarCodeReader`デフォルト値を持つクラス. ReadBarCodes() メソッドを呼び出す前に画像を設定する必要があります (SetBitmapImage()). |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | の新しいインスタンスを初期化します`BarCodeReader`画像からのクラス. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | の新しいインスタンスを初期化します`BarCodeReader` file. からのクラス |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | の新しいインスタンスを初期化します`BarCodeReader`class. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | の新しいインスタンスを初期化します`BarCodeReader`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | 主なバーコード デコード パラメータ。認識されたデータに影響を与えるパラメータが含まれています. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | 認識される[`BarCodeResult`](../barcoderesult/)の配列 |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | 認識されたバーコード数を取得します |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings を使用すると、認識の品質と速度を手動で構成できます。 組み込みのプリセット (HighPerformance、NormalQuality、 HighQuality、MaxBarCodes) によって QualitySettings をすばやくセットアップできます。または、個別のオプションを手動で構成することもできます。 QualitySettings のデフォルト値は NormalQuality です。 |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | ミリ秒単位で認識プロセスのタイムアウトを取得または設定します。 |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | プロセッサ コアを使用する設定を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | 指定された xml-stream から BarCode プロパティをインポートし、それらを現在の BarCodeReader インスタンスに適用します。 |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | 指定された xml ファイルから BarCode プロパティをインポートし、それらを現在の BarCodeReader インスタンスに適用します。 |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | 関数は、他のスレッドからの現在の認識セッションの終了を要求します。 Abort はブロックできないメソッドであり、呼び出しの直後に制御を返します。 このメソッドは、認識プロセスが長すぎる場合に使用する必要があります. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | 指定された xml-stream にバーコード プロパティをエクスポートします |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | 指定された xml ファイルにバーコード プロパティをエクスポートします |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | 読み取り[`BarCodeResult`](../barcoderesult/)画像からのs. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | 認識用のビットマップ イメージを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | 認識用の画像ストリームを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | 認識用の画像ファイルを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | ビットマップ画像と認識領域を設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | 認識用のビットマップ イメージと領域を設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | 認識用のデコード タイプを設定します。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | セット[`SingleDecodeType`](../singledecodetype/)認識用の型配列。 ReadBarCodes() メソッドの前に呼び出す必要があります。 |

### 例

このサンプルは、Code39 および Code128 バーコードを検出する方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 関連項目

* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

---
title: BarcodeGenerator
second_title: Aspose.BarCode for.NETAPIリファレンス
description: バックエンド バーコード画像生成用の BarcodeGenerator.
type: docs
weight: 700
url: /ja/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

バックエンド バーコード画像生成用の BarcodeGenerator.

supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14 、SingaporePost ... 2D: Aztec、DataMatrix、PDf417、QR コード ...

```csharp
public sealed class BarcodeGenerator : Component
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | BarcodeGenerator. のインスタンスを作成します。 |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | BarcodeGenerator. のインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | バーコード記号タイプ. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | エンコードするテキスト. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | 生成パラメータ. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | 指定された xml-stream から BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。 |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | 指定された xml ファイルから BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。 |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | WPF キャンバスにバーコード イメージを描画します。 |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | 指定された xml-stream にバーコード プロパティをエクスポートします |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | 指定された xml ファイルにバーコード プロパティをエクスポートします |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | 現在の設定でバーコード イメージを生成します。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | バーコード イメージを特定のファイルに保存します。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | バーコード イメージを特定の形式でストリームに保存します。 |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | バーコード イメージを特定の形式で特定のファイルに保存します。 |

### 例

このサンプルでは、バーコード イメージを作成して保存する方法を示します。

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### 関連項目

* 名前空間 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
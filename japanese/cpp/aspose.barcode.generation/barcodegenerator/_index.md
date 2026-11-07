---
title: "Aspose::BarCode::Generation::BarcodeGenerator クラス"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::BarcodeGenerator クラス。C++ でバックエンドのバーコード画像生成のための BarcodeGenerator。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | [BarcodeGenerator](./) のインスタンスを作成します。 |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | [BarcodeGenerator](./) のインスタンスを作成します。 |
| [Dispose](./dispose/)() override | 使用中のリソースをクリーンアップします。 |
| [ExportToXml](./exporttoxml/)(System::String) | [BarCode](../../aspose.barcode/) のプロパティを指定された XML ファイルにエクスポートします |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | [BarCode](../../aspose.barcode/) のプロパティを指定された XML ストリームにエクスポートします |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | 現在の設定でバーコード画像を生成します。 |
| [get_BarcodeType](./get_barcodetype/)() | バーコードシンボロジータイプ。 |
| [get_CodeText](./get_codetext/)() | エンコードするテキスト。 |
| [get_Parameters](./get_parameters/)() const | [Generation](../) パラメーター。 |
| static [ImportFromXml](./importfromxml/)(System::String) | 指定された XML ファイルから [BarCode](../../aspose.barcode/) プロパティをインポートし、[BarcodeGenerator](./) インスタンスを作成します。 |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | 指定された XML ストリームから [BarCode](../../aspose.barcode/) プロパティをインポートし、[BarcodeGenerator](./) インスタンスを作成します。 |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | バーコード画像を特定の形式でストリームに保存します。 |
| [Save](./save/)(System::String, BarCodeImageFormat) | バーコード画像を特定の形式で特定のファイルに保存します。 |
| [Save](./save/)(System::String) | バーコード画像を特定のファイルに保存します。 |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | バーコードシンボロジータイプ。 |
| [set_CodeText](./set_codetext/)(System::String) | エンコードするテキスト。 |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | codetext をバイト列として設定します。 |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## 備考


サポートされているシンボロジー: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

このサンプルはバーコード画像の作成と保存方法を示しています。
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

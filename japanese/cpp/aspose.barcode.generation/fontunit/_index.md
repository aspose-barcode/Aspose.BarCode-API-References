---
title: "Aspose::BarCode::Generation::FontUnit クラス"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::Generation::FontUnit クラス。テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは C++ の Unit 値プロパティで指定されます。"
type: docs
weight: 2500
url: /ja/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


テキストの特定のフォーマットを定義し、フォントファミリー、サイズ、スタイル属性を含み、サイズは [Unit](../unit/) 値プロパティで指定されます。

```cpp
class FontUnit : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | このフォントのフェイス名を取得します。 |
| [get_Size](./get_size/)() const | この [FontUnit](./) のサイズを [Unit](../unit/) の値として取得します。 |
| [get_Style](./get_style/)() const | この [FontUnit](./) のスタイル情報を取得します。 |
| [set_FamilyName](./set_familyname/)(System::String) | このフォントのフェイス名を設定します。 |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | この [FontUnit](./) のスタイル情報を設定します。 |
## 備考


このサンプルは、[BarCode](../../aspose.barcode/) 画像を作成して保存する方法を示しています。
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

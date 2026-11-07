---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " enum. C++における2Dコンポーネントのタイプ。"
type: docs
weight: 8700
url: /ja/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


2D コンポーネントのタイプ

```cpp
enum class TwoDComponentType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| 自動 | 0 | 2Dコンポーネントのタイプを自動選択 |
| CC_A | 1 | CC-Aは2Dコンポーネントのタイプです。MicroPDF417の構造的バリアントです。 |
| CC_B | 2 | CC-Bは2Dコンポーネントのタイプです。MicroPDF417シンボルです。 |
| CC_C | 3 | CC-Cは2Dコンポーネントのタイプです。PDF417シンボルです。 |

## 備考


このサンプルはGS1コンポジットバー画像の作成と保存方法を示します。1Dコードテキストと2Dコードテキストは記号'/'で区切られていることに注意してください。
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // 2Dコンポーネントのアスペクト比
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // 1Dおよび2DコンポーネントのX寸法
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // 1Dコンポーネントの高さ
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

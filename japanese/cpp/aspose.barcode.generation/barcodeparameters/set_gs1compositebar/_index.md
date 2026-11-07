---
title: "メソッド"
linktitle: "set_GS1CompositeBar"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. C++ の GS1 Composite Bar パラメータ。"
type: docs
weight: 2600
url: /ja/cpp/aspose.barcode.generation/barcodeparameters/set_gs1compositebar/
---
## BarcodeParameters::set_GS1CompositeBar method


GS1 コンポジットバーのパラメータ。

```cpp
void Aspose::BarCode::Generation::BarcodeParameters::set_GS1CompositeBar(System::SharedPtr<GS1CompositeBarParameters> value)
```

## 備考


このサンプルは、GS1 Composite Bar 画像の作成と保存方法を示しています。1D コードテキストと 2D コードテキストはシンボル '|' で区切られることに注意してください。
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
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

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

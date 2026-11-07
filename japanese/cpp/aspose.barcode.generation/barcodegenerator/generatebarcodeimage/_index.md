---
title: "メソッド"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。C++で現在の設定に基づいてバーコード画像を生成します。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


現在の設定でバーコード画像を生成します。

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

バーコード画像。[Bitmap](../) を参照してください。
## 備考



このサンプルはバーコード画像の作成と保存方法を示しています。
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## 関連項目

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

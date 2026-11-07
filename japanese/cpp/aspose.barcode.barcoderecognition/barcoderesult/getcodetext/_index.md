---
title: "メソッド"
linktitle: "GetCodeText"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++でエンコーディング付きのコードテキストを取得します。"
type: docs
weight: 1000
url: /ja/cpp/aspose.barcode.barcoderecognition/barcoderesult/getcodetext/
---
## BarCodeResult::GetCodeText method


エンコードされたコードテキストを取得します。

```cpp
System::String Aspose::BarCode::BarCodeRecognition::BarCodeResult::GetCodeText(System::SharedPtr<System::Text::Encoding> encoding)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| エンコーディング | System::SharedPtr\<System::Text::Encoding\> | コードテキストのエンコーディング。 |

### ReturnValue

認識されたコードテキストを含む文字列。
## 備考



この例は **GetCodeText** の使用方法を示しています：


```cpp
[C#]
    using (BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DataMatrix))
    {
        gen.SetCodeText("車種名", Encoding.GetEncoding(932));
        gen.Save("barcode.png", BarCodeImageFormat.Png);
    }
    using (BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DataMatrix))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.GetCodeText(Encoding.GetEncoding(932)));
```

## 関連項目

* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

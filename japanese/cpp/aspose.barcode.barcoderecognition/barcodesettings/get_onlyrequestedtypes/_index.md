---
title: "メソッド"
linktitle: "get_OnlyRequestedTypes"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. 認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は C++ では false です。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_onlyrequestedtypes/
---
## BarcodeSettings::get_OnlyRequestedTypes method


認識のために明示的に指定されたバーコードタイプのみを返します。有効にすると、他の互換または同等のタイプの認識されたバーコードは除外されます。デフォルト値は false です。

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_OnlyRequestedTypes() const
```

## 備考


このサンプルは、認識結果を要求されたバーコードタイプのみに制限する方法を示しています。
```cpp
[C#]
//EAN13 バーコードを生成する
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//UPCA バーコードのみを認識する（ソースが EAN13 のため結果はありません）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//互換タイプを認識する: EAN13、UPCA、ISSN、ISMN、ISBN（EAN13 は UPCA と同等として返されます）
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


認識のために明示的に指定されたバーコードタイプのみを返します。デフォルト値は false です。
## 関連項目

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

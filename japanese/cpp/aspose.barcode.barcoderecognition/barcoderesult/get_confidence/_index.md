---
title: "メソッド"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。認識されたバーコードの認識信頼度レベルを取得します（C++）。"
type: docs
weight: 200
url: /ja/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


認識されたバーコードの信頼度レベルを取得します

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## 備考


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## 関連項目

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)

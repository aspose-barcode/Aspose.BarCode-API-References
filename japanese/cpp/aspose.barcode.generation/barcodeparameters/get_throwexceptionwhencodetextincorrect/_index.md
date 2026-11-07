---
title: "メソッド"
linktitle: "get_ThrowExceptionWhenCodeTextIncorrect"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。そうでない場合は、codetext がバーコードの仕様に合わせて修正されます。例外が常にスローされるケース: codetext が正しくない場合の Databar シンボロジー。例外が常にスローされないケース: C++ で codetext が正しくない場合の AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジー。"
type: docs
weight: 1200
url: /ja/cpp/aspose.barcode.generation/barcodeparameters/get_throwexceptionwhencodetextincorrect/
---
## BarcodeParameters::get_ThrowExceptionWhenCodeTextIncorrect method


1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。それ以外の場合、codetext はバーコードの仕様に合わせて修正されます。例外は常にスローされます: Databar シンボロジーで codetext が正しくない場合。例外がスローされないのは常に次の場合です: AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジーで codetext が正しくない場合。

```cpp
bool Aspose::BarCode::Generation::BarcodeParameters::get_ThrowExceptionWhenCodeTextIncorrect() const
```

## 関連項目

* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)

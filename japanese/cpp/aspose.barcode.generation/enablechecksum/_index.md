---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "C++でenumを使用する方法。"
type: docs
weight: 6700
url: /ja/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| デフォルト | 0 | 仕様でチェックサムが必要とされる場合、チェックサムが付加されます。 |
| はい | 1 | 可能な限り常にチェックサムを使用してください。 |
| いいえ | 2 | チェックサムを使用しないでください。 |

## 備考


1次元バーコードの生成時にチェックサムを有効にします。

デフォルトは、チェックサムが必須のシンボロジーでは「はい」とみなされ、チェックサムが可能なだけのシンボロジーでは「いいえ」とみなされます。

チェックサムは使用されません: Codabar

チェックサムは可能です: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

チェックサムが常に使用される: その他のシンボロジー
## 関連項目

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)

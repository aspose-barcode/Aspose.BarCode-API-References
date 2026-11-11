---
title: "QrParameters.EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "QrParameters プロパティ。QR および RectMicroQR バーコードで GS1 の特殊文字をバイトモードでエンコードするかどうかを示す値を取得または設定します。"
type: docs
weight: 30
url: /ja/net/aspose.barcode.generation/qrparameters/encodegs1separatorinbytemode/
---
## QrParameters.EncodeGS1SeparatorInByteMode property

GS1 の特殊文字を QR および RectMicroQR バーコードでバイトモードでエンコードするかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

```csharp
public bool EncodeGS1SeparatorInByteMode { get; set; }
```

### 関連項目

* class [QrParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)



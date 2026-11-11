---
title: "BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "BarcodeGeneratorElement プロパティ。 GS1 の特殊文字を QR および RectMicroQR バーコードでバイトモードでエンコードするかどうかを示す値を取得または設定します"
type: docs
weight: 1290
url: /ja/net/aspose.barcode.wpf/barcodegeneratorelement/qrencodegs1separatorinbytemode/
---
## BarcodeGeneratorElement.QREncodeGS1SeparatorInByteMode property

GS1 の特殊文字を QR および RectMicroQR バーコードでバイトモードでエンコードするかどうかを示す値を取得または設定します。

false の場合、QR 仕様に従い、GS1 区切り文字は英数字モードで '%' としてエンコードされる可能性があります。

true の場合、GS1 グループ区切り文字はバイトモードで 0x1D 文字としてエンコードされ、'%' 文字もデータとして保持するためにバイトモードでエンコードされます。

このオプションは、バイトレベルの GS1 グループ区切り文字を期待するデコーダとの互換性を向上させ、'%' データ文字が GS1 区切り文字として解釈されるのを防止します。

```csharp
public bool QREncodeGS1SeparatorInByteMode { get; set; }
```

### 関連項目

* class [BarcodeGeneratorElement](../)
* namespace [Aspose.BarCode.WPF](../../../aspose.barcode.wpf/)
* assembly [Aspose.BarCode](../../../)



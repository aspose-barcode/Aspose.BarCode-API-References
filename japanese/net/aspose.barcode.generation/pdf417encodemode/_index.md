---
title: "列挙体 Pdf417EncodeMode"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.Generation.Pdf417EncodeMode 列挙体。Pdf417 バーコードのエンコードモード"
type: docs
weight: 1540
url: /ja/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Pdf417 バーコードのエンコードモード

```csharp
public enum Pdf417EncodeMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Auto | `0` | Autoモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字は、指定されたECIEncodingで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。 |
| Binary | `1` | Binaryモードでは、CodeTextは最大のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。 |
| ECI | `2` | ECIモードでは、メッセージ全体が指定されたECIEncodingで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、一部の古い（2006年以前の）スキャナーはこのモードをサポートしていない可能性があります。 |
| Extended | `3` | マルチECIモードをサポートする拡張モードです。 |

### 関連項目

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)



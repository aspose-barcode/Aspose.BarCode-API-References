---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode for.NETAPIリファレンス
description: HIBC LIC のセカンダリ データと追加データを格納するためのクラス
type: docs
weight: 590
url: /ja/net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class

HIBC LIC のセカンダリ データと追加データを格納するためのクラス。

```csharp
public class SecondaryAndAdditionalData
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [SecondaryAndAdditionalData](secondaryandadditionaldata/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DateOfManufacture](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/dateofmanufacture/) { get; set; } | 製造日を識別します。 このフィールドを使用しないために、製造日を DateTime.MinValue に設定できます。 デフォルト値: DateTime.MinValue |
| [ExpiryDate](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydate/) { get; set; } | 有効期限を識別します。 ExpiryDateFormat が None に設定されていない場合に使用されます。 |
| [ExpiryDateFormat](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/expirydateformat/) { get; set; } | 有効期限の形式を識別します。 |
| [LotNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/lotnumber/) { get; set; } | ロットまたはバッチ番号を識別します。ロット/バッチ番号は、最大 18 sybmol の長さの英数字の文字列である必要があります。 . |
| [Quantity](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/quantity/) { get; set; } | 数量を識別します。0 から 500 までの整数値でなければなりません。 このフィールドを使用しないために、数量を -1 に設定できます。 デフォルト値: -1 |
| [SerialNumber](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/serialnumber/) { get; set; } | シリアル番号を識別します。シリアル番号は、最大 18 sybmol の長さの英数字の文字列でなければなりません. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/equals/)(object) | このインスタンスが指定された値と等しいかどうかを示す値を返します`SecondaryAndAdditionalData`値. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| [ParseFromString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/parsefromstring/)(string) | HIBC LIC 仕様に従って、文字列形式からセカンダリおよび追加の補足データをインスタンス化します。 |
| override [ToString](../../aspose.barcode.complexbarcode/secondaryandadditionaldata/tostring/)() | HIBC LIC 仕様に従って、データを文字列形式に変換します。 |

### 関連項目

* 名前空間 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
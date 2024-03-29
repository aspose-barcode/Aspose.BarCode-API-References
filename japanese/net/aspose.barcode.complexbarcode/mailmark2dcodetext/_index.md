---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for.NETAPIリファレンス
description: Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするためのクラス.
type: docs
weight: 470
url: /ja/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするためのクラス.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | アイテムのクラスを識別します。 |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | 顧客が使用するオプションのスペース. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Datamatrix バーコードのエンコードモード. デフォルト値: DataMatrixEncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark Type は Data Matrix バーコードのサイズを定義します. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | 配送先住所の郵便番号と DPS 内陸の場合、郵便番号/DP には次の文字数が含まれます. エリア (1 または 2 文字) 地区 (1 または 2 文字) セクター (1 文字) ユニット (2 文字) DPS (2 文字). 郵便番号と DPS は、有効な PAF® 形式に準拠する必要があります. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | 各製品タイプの Royal Mail Mailmark バーコード ペイロードを識別します。 |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | サプライ チェーン ID 内の一意のアイテムを識別します。 すべてのメールマーク バーコードには ID を付ける必要があるため、少なくとも 90 日間一意に識別できます。 最大値: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Return to Sender Post Code が含まれていますが、DPS は含まれていません。 PC (DPS なし) は PAF® フォーマットに準拠している必要があります。 |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | どのレベルの差出人への返信サービスが要求されているかを示すフラグ。 |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | 郵送に関係する一意の顧客グループを識別します。 最大値: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | UPU 国 ID を識別します。最大長: 4 文字。 |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | 各情報タイプ ID に関連するバーコード バージョンを識別します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | バーコードの種類を取得します。 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Mailmark データから codetext を作成します。 |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | 構築されたコードテキストからメールマーク データを初期化します。 |

### 関連項目

* interface [IComplexCodetext](../icomplexcodetext/)
* 名前空間 [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

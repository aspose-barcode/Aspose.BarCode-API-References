---
title: "クラス USADriveIdCodetext"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext クラス。USA運転免許証のPDF417コードに埋め込まれたテキストをエンコードおよびデコードするためのクラス"
type: docs
weight: 810
url: /ja/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

USA運転免許証のPDF417コードに埋め込まれたテキストをエンコードおよびデコードするクラスです。

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA バージョン番号 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | この番号は発行管轄を一意に識別し、ISO 発行機関（AAMVA）に問い合わせることで取得できます。6桁の完全な IIN をエンコードする必要があります。 |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | 管轄固有フィールド |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | 管轄バージョン番号 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | カードの必須要素（フィールド） |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | サブファイルの番号 00-99 |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | カードのオプション要素（フィールド） |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | 以下のサブファイル、タイプ、オフセット、長さに関する情報が含まれます。重要: タイプのみ設定すると、オフセットと長さは自動的に設定されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | USA DL（Pdf417）のバーコードタイプを返します |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | USA DL データからコードテキストを構築します |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | コードテキストから USA DL オブジェクトを初期化します |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | XML に保存します |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | カードの必須要素（フィールド） |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | カードのオプション要素（フィールド） |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL サブファイルプロパティ、オフセットと長さは自動的に設定されます。 |

### 関連項目

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



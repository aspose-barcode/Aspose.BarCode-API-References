---
title: EncodeTypes
second_title: Aspose.BarCode for.NETAPIリファレンス
description: エンコードするバーコードのタイプを指定します
type: docs
weight: 950
url: /ja/net/aspose.barcode.generation/encodetypes/
---
## EncodeTypes class

エンコードするバーコードのタイプを指定します。

```csharp
public static class EncodeTypes
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [AllEncodeTypes](../../aspose.barcode.generation/encodetypes/allencodetypes/) { get; } | 使用可能なすべてのシンボル体系でデータをチェックすることを指定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetNames](../../aspose.barcode.generation/encodetypes/getnames/)() | エンコード タイプの名前の配列を取得します。 |
| static [Parse](../../aspose.barcode.generation/encodetypes/parse/)(string, out BaseEncodeType) | BaseEncodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。 |
| static [TryParse](../../aspose.barcode.generation/encodetypes/tryparse/)(string, out BaseEncodeType) | BaseEncodeType の文字列表現をそのインスタンスに変換します。 戻り値は、変換が成功したか失敗したかを示します。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [AustralianPosteParcel](../../aspose.barcode.generation/encodetypes/australianposteparcel/) | データをエンコードする必要があることを指定します **オーストラリア郵便の国内 eParcel バーコード**バーコード仕様 |
| static readonly [AustraliaPost](../../aspose.barcode.generation/encodetypes/australiapost/) | オーストラリア郵便の顧客を表します BarCode |
| static readonly [Aztec](../../aspose.barcode.generation/encodetypes/aztec/) | データをエンコードする必要があることを指定します **アステカ**バーコード仕様 |
| static readonly [Codabar](../../aspose.barcode.generation/encodetypes/codabar/) | データをエンコードする必要があることを指定します **コーダバー**バーコード仕様 |
| static readonly [CodablockF](../../aspose.barcode.generation/encodetypes/codablockf/) | データをエンコードする必要があることを指定します **Codablock-F**バーコード仕様. |
| static readonly [Code11](../../aspose.barcode.generation/encodetypes/code11/) | データをエンコードする必要があることを指定します **コード 11**バーコード仕様 |
| static readonly [Code128](../../aspose.barcode.generation/encodetypes/code128/) | データをエンコードする必要があることを指定します **コード 128**バーコード仕様 |
| static readonly [Code16K](../../aspose.barcode.generation/encodetypes/code16k/) | Code 16K バーコードを表します。 |
| static readonly [Code32](../../aspose.barcode.generation/encodetypes/code32/) | データをエンコードする必要があることを指定します **Code32**バーコード仕様 |
| static readonly [Code39Extended](../../aspose.barcode.generation/encodetypes/code39extended/) | データをエンコードする必要があることを指定します **拡張コード 39**バーコード仕様 |
| static readonly [Code39Standard](../../aspose.barcode.generation/encodetypes/code39standard/) | データをエンコードする必要があることを指定します **標準コード 39**バーコード仕様 |
| static readonly [Code93Extended](../../aspose.barcode.generation/encodetypes/code93extended/) | データをエンコードする必要があることを指定します **拡張コード 93**バーコード仕様 |
| static readonly [Code93Standard](../../aspose.barcode.generation/encodetypes/code93standard/) | データをエンコードする必要があることを指定します **標準コード 93**バーコード仕様 |
| static readonly [DatabarExpanded](../../aspose.barcode.generation/encodetypes/databarexpanded/) | GS1 Databar 拡張バーコードを表します。 |
| static readonly [DatabarExpandedStacked](../../aspose.barcode.generation/encodetypes/databarexpandedstacked/) | GS1 Databar 拡張スタック バーコードを表します。 |
| static readonly [DatabarLimited](../../aspose.barcode.generation/encodetypes/databarlimited/) | GS1 Databar 限定バーコードを表します。 |
| static readonly [DatabarOmniDirectional](../../aspose.barcode.generation/encodetypes/databaromnidirectional/) | データをエンコードする必要があることを指定します **GS1 Databar 無指向性**バーコード仕様. |
| static readonly [DatabarStacked](../../aspose.barcode.generation/encodetypes/databarstacked/) | GS1 Databar スタック バーコードを表します。 |
| static readonly [DatabarStackedOmniDirectional](../../aspose.barcode.generation/encodetypes/databarstackedomnidirectional/) | GS1 Databar スタック全方向バーコードを表します。 |
| static readonly [DatabarTruncated](../../aspose.barcode.generation/encodetypes/databartruncated/) | データをエンコードする必要があることを指定します **GS1 データバーが切り捨てられました**バーコード仕様. |
| static readonly [DataLogic2of5](../../aspose.barcode.generation/encodetypes/datalogic2of5/) | データをエンコードする必要があることを指定します **DataLogic 2/5**バーコード仕様 |
| static readonly [DataMatrix](../../aspose.barcode.generation/encodetypes/datamatrix/) | 2D バーコード記号 DataMatrix |
| static readonly [DeutschePostIdentcode](../../aspose.barcode.generation/encodetypes/deutschepostidentcode/) | Deutsch Post バーコードを表します。この記号は、Identcode、CodeIdentcode、German Postal 2 of 5 Identcode、 Deutsch Post AG Identcode、Deutsch Frachtpost Identcode、Deutsch Post AG (DHL) とも呼ばれます。 |
| static readonly [DeutschePostLeitcode](../../aspose.barcode.generation/encodetypes/deutschepostleitcode/) | Deutsch Post Leitcode Barcode を表します。これは、German Postal 2 of 5 Leitcode、CodeLeitcode、Leitcode、Deutsch Post AG (DHL) とも呼ばれます。 |
| static readonly [DotCode](../../aspose.barcode.generation/encodetypes/dotcode/) | データをエンコードする必要があることを指定します **ドットコード**バーコード仕様 |
| static readonly [DutchKIX](../../aspose.barcode.generation/encodetypes/dutchkix/) | データをエンコードする必要があることを指定します **オランダ航空**バーコード仕様 |
| static readonly [EAN13](../../aspose.barcode.generation/encodetypes/ean13/) | データをエンコードする必要があることを指定します **EAN-13**バーコード仕様 |
| static readonly [EAN14](../../aspose.barcode.generation/encodetypes/ean14/) | データをエンコードする必要があることを指定します **EAN14**バーコード仕様 |
| static readonly [EAN8](../../aspose.barcode.generation/encodetypes/ean8/) | データをエンコードする必要があることを指定します **EAN-8**バーコード仕様 |
| static readonly [GS1CodablockF](../../aspose.barcode.generation/encodetypes/gs1codablockf/) | データをエンコードする必要があることを指定します **GS1 コーダブロック-F**バーコード仕様。コードテキストには、AI. の括弧が含まれている必要があります。 |
| static readonly [GS1Code128](../../aspose.barcode.generation/encodetypes/gs1code128/) | データをエンコードする必要があることを指定します **GS1 コード 128**バーコード仕様。コードテキストには、AI. の括弧が含まれている必要があります。 |
| static readonly [GS1CompositeBar](../../aspose.barcode.generation/encodetypes/gs1compositebar/) | データをエンコードする必要があることを指定します **GS1 コンポジットバー**バーコード仕様。コードテキストには、AI の括弧が含まれている必要があります。 1D コードテキストと 2D コードテキストは、記号 '/' で区切る必要があります |
| static readonly [GS1DataMatrix](../../aspose.barcode.generation/encodetypes/gs1datamatrix/) | GS1 文字列形式の 2D バーコード シンボル DataMatrix |
| static readonly [GS1DotCode](../../aspose.barcode.generation/encodetypes/gs1dotcode/) | データをエンコードする必要があることを指定します **GS1ドットコード**バーコード仕様。コードテキストには、AI. の括弧が含まれている必要があります。 |
| static readonly [GS1QR](../../aspose.barcode.generation/encodetypes/gs1qr/) | GS1 文字列付きの 2D バーコード記号 QR format |
| static readonly [HIBCAztecLIC](../../aspose.barcode.generation/encodetypes/hibcazteclic/) | データをエンコードする必要があることを指定します **HIBC LIC アステカ**バーコード仕様。 |
| static readonly [HIBCAztecPAS](../../aspose.barcode.generation/encodetypes/hibcaztecpas/) | データをエンコードする必要があることを指定します **HIBC PAS アズテック**バーコード仕様。 |
| static readonly [HIBCCode128LIC](../../aspose.barcode.generation/encodetypes/hibccode128lic/) | データをエンコードする必要があることを指定します **HIBC LICコード128**バーコード仕様。 |
| static readonly [HIBCCode128PAS](../../aspose.barcode.generation/encodetypes/hibccode128pas/) | データをエンコードする必要があることを指定します **HIBC PAS Code128**バーコード仕様。 |
| static readonly [HIBCCode39LIC](../../aspose.barcode.generation/encodetypes/hibccode39lic/) | データをエンコードする必要があることを指定します **HIBC LIC Code39スタンダード**バーコード仕様。 |
| static readonly [HIBCCode39PAS](../../aspose.barcode.generation/encodetypes/hibccode39pas/) | データをエンコードする必要があることを指定します **HIBC PAS Code39スタンダード**バーコード仕様。 |
| static readonly [HIBCDataMatrixLIC](../../aspose.barcode.generation/encodetypes/hibcdatamatrixlic/) | データをエンコードする必要があることを指定します **HIBC LIC データマトリックス**バーコード仕様。 |
| static readonly [HIBCDataMatrixPAS](../../aspose.barcode.generation/encodetypes/hibcdatamatrixpas/) | データをエンコードする必要があることを指定します **HIBC PAS データマトリックス**バーコード仕様。 |
| static readonly [HIBCQRLIC](../../aspose.barcode.generation/encodetypes/hibcqrlic/) | データをエンコードする必要があることを指定します **HIBC LIC QR**バーコード仕様。 |
| static readonly [HIBCQRPAS](../../aspose.barcode.generation/encodetypes/hibcqrpas/) | データをエンコードする必要があることを指定します **HIBC PAS QR**バーコード仕様。 |
| static readonly [IATA2of5](../../aspose.barcode.generation/encodetypes/iata2of5/) | IATA 2 of 5 バーコードを表します。IATA (国際航空運送協会) は、このバーコードを航空貨物の管理に使用しています。 |
| static readonly [Interleaved2of5](../../aspose.barcode.generation/encodetypes/interleaved2of5/) | データをエンコードする必要があることを指定します **インターリーブ 2 の 5**バーコード仕様 |
| static readonly [ISBN](../../aspose.barcode.generation/encodetypes/isbn/) | データをエンコードする必要があることを指定します **ISBN**バーコード仕様 |
| static readonly [ISMN](../../aspose.barcode.generation/encodetypes/ismn/) | データをエンコードする必要があることを指定します **ISMN**バーコード仕様 |
| static readonly [ISSN](../../aspose.barcode.generation/encodetypes/issn/) | データをエンコードする必要があることを指定します **ISSN**バーコード仕様 |
| static readonly [ItalianPost25](../../aspose.barcode.generation/encodetypes/italianpost25/) | イタリア郵便 25 バーコードを表します。 |
| static readonly [ITF14](../../aspose.barcode.generation/encodetypes/itf14/) | データをエンコードする必要があることを指定します **ITF14**バーコード仕様 |
| static readonly [ITF6](../../aspose.barcode.generation/encodetypes/itf6/) | ITF-6 バーコードを表します。 |
| static readonly [MacroPdf417](../../aspose.barcode.generation/encodetypes/macropdf417/) | データをエンコードする必要があることを指定します **MacroPdf417**バーコード仕様 |
| static readonly [Mailmark](../../aspose.barcode.generation/encodetypes/mailmark/) | Royal Mail Mailmark バーコードを表します。 |
| static readonly [Matrix2of5](../../aspose.barcode.generation/encodetypes/matrix2of5/) | Matrix 2 of 5 を表します BarCode |
| static readonly [MaxiCode](../../aspose.barcode.generation/encodetypes/maxicode/) | データをエンコードする必要があることを指定します **マキシコード**バーコード仕様 |
| static readonly [MicroPdf417](../../aspose.barcode.generation/encodetypes/micropdf417/) | データをエンコードする必要があることを指定します **MicroPdf417**バーコード仕様 |
| static readonly [MSI](../../aspose.barcode.generation/encodetypes/msi/) | データをエンコードする必要があることを指定します **MSIプレッシー**バーコード仕様 |
| static readonly [None](../../aspose.barcode.generation/encodetypes/none/) | 未指定のエンコード タイプ。 |
| static readonly [OneCode](../../aspose.barcode.generation/encodetypes/onecode/) | データを USPS でエンコードする必要があることを指定します **ワンコード**バーコード仕様 |
| static readonly [OPC](../../aspose.barcode.generation/encodetypes/opc/) | OPC (Optical Product Code) バーコードを表し、VCA Barcode VCA OPC、Vision Council of America OPC Barcode とも呼ばれます。 |
| static readonly [PatchCode](../../aspose.barcode.generation/encodetypes/patchcode/) | パッチコードを表します バーコード |
| static readonly [Pdf417](../../aspose.barcode.generation/encodetypes/pdf417/) | データをエンコードする必要があることを指定します **PDF417**バーコード仕様 |
| static readonly [Pharmacode](../../aspose.barcode.generation/encodetypes/pharmacode/) | Pharmacode バーコードを表します。 |
| static readonly [Planet](../../aspose.barcode.generation/encodetypes/planet/) | データをエンコードする必要があることを指定します **星**バーコード仕様 |
| static readonly [Postnet](../../aspose.barcode.generation/encodetypes/postnet/) | データをエンコードする必要があることを指定します **ポストネット**バーコード仕様 |
| static readonly [PZN](../../aspose.barcode.generation/encodetypes/pzn/) | PZN バーコードを表します。この記号は、薬局中央番号、Pharmazentralnummer としても知られています。 |
| static readonly [QR](../../aspose.barcode.generation/encodetypes/qr/) | データをエンコードする必要があることを指定します **QRコード**バーコード仕様 |
| static readonly [RM4SCC](../../aspose.barcode.generation/encodetypes/rm4scc/) | RM4SCC バーコードを表します。 RM4SCC (Royal Mail 4-state Customer Code) は、英国の自動郵便仕分けプロセスに使用されます. |
| static readonly [SCC14](../../aspose.barcode.generation/encodetypes/scc14/) | データをエンコードする必要があることを指定します **SCC14**バーコード仕様 |
| static readonly [SingaporePost](../../aspose.barcode.generation/encodetypes/singaporepost/) | データをエンコードする必要があることを指定します **シンガポール郵便バーコード**バーコード仕様 |
| static readonly [SSCC18](../../aspose.barcode.generation/encodetypes/sscc18/) | データをエンコードする必要があることを指定します **SSCC18**バーコード仕様 |
| static readonly [Standard2of5](../../aspose.barcode.generation/encodetypes/standard2of5/) | データをエンコードする必要があることを指定します **標準 2 の 5**バーコード仕様 |
| static readonly [SwissPostParcel](../../aspose.barcode.generation/encodetypes/swisspostparcel/) | データをエンコードする必要があることを指定します **スイス郵便小包バーコード**バーコード仕様。サポートされているタイプ: 国内郵便、国際郵便、追加サービス (新規) |
| static readonly [UPCA](../../aspose.barcode.generation/encodetypes/upca/) | データをエンコードする必要があることを指定します **UPC-A**バーコード仕様 |
| static readonly [UpcaGs1Code128Coupon](../../aspose.barcode.generation/encodetypes/upcags1code128coupon/) | データをエンコードする必要があることを指定します **GS1-128 拡張コード付き UPC クーポン**バーコード仕様. 入力文字列の例: BarcodeGenerator.Codetext = "514141100906(8102)03", ここで、UPCA 部分は「514141100906」、GS1Code128 部分は (8102)03. |
| static readonly [UpcaGs1DatabarCoupon](../../aspose.barcode.generation/encodetypes/upcags1databarcoupon/) | データをエンコードする必要があることを指定します **GS1 DataBar を追加した UPC クーポン**barcode specification. An example of the input string: BarcodeGenerator.Codetext = "514141100906(8110)106141416543213500110000310123196000", where UPCA part is "514141100906", Databar part is "(8110)106141416543213500110000310123196000". To change the caption, use Parameters.CaptionAbove.Text = "会社のプレフィックス + オファー コード"; |
| static readonly [UPCE](../../aspose.barcode.generation/encodetypes/upce/) | データをエンコードする必要があることを指定します **UPC-E**バーコード仕様 |
| static readonly [VIN](../../aspose.barcode.generation/encodetypes/vin/) | VIN (車両識別番号) バーコードを表します。 |

### 関連項目

* 名前空間 [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->

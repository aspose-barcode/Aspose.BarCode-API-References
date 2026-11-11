---
title: "クラス USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields クラス。カードのオプション要素フィールド"
type: docs
weight: 830
url: /ja/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

カードのオプション要素（フィールド）

```csharp
public class OptionalFields
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH、カード所有者住所の通り部分の2行目、DL/ID、V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN、カード所有者が知られている他の姓、DL/ID、V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG、カード所有者が知られている他の名、DL/ID、V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS、カード所有者が知られている他の接尾辞、DL/ID、V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ、運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（文字と/または数字）。カードまたは MRT で監査情報が使用されていない場合は、運転者レコードに含める必要があります、DL/ID、V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB、DHSが必須とするフィールドで、DL/IDの表示形式の最新バージョン変更または修正の日付を示します。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA、DHSが必須とするフィールドで、コンプライアンスを示します：“F”＝準拠、 “N”＝非準拠、DL/ID、F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ、管轄固有のコードが示す、車両クラスを超えてカード所有者に付与される追加の運転特権を説明するテキスト、DL、V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ、禿頭、黒、ブロンド、茶、灰、赤/オーバーン、サンド、白、未知。発行管轄が色を省略したい場合は、AAMVA D20で提供される3文字コードを使用する必要があります、DL/ID、V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC、文書によって付与された危険物取扱承認が無効になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL、F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK、運転免許証やIDカードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列（英数字）。（DHS推奨フィールド）、DL/ID、V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD、DHSが必須とするフィールドで、カード所有者が一時的な合法ステータスを持つことを示します＝“1”、DL/ID、F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU、名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS等）に参加している場合、サフィックスはDL/IDおよびMRTに収集・表示される必要があります）。JR（ジュニア）、SR（シニア）、1STまたはI（ファースト）、9THまたはIX（ナインス）まで、DL/ID、V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK、カード所有者が臓器提供者であることを示すフィールド＝“1”、DL/ID、F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI、国および自治体、または州/県、DL/ID、V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL、AAMVA D20で定義されたカード所有者の人種または民族のコード、DL/ID、V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR、運転特権を制限する管轄固有の制限コードを説明するテキスト、DL、V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN、カード所有者の標準エンドースメントコード。D20のコードを参照してください。このデータ要素は、エンドースメントコードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO、カード所有者の標準制限コード。D20のコードを参照してください。このデータ要素は、制限コードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM、カード所有者の標準車両分類コード。このデータ要素は、車両分類の標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH、カード所有者が18歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI、カード所有者が19歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ、カード所有者が21歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP、カード所有者が運転許可を受けている車両分類の管轄固有コードを説明するテキスト、DL、V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL、カード所有者がベテランであることを示すフィールド＝“1”、DL/ID、F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX、カード所有者の体重（キログラム）。例：84 kg = “084”、DL/ID、F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW、カード所有者の体重（ポンド）。例：185 lb = “185”、DL/ID、F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE、カード所有者の概算体重範囲を示します：0 = 31 kgまで（70 lbsまで）、1 = 32–45 kg（71–100 lbs）、2 = 46–59 kg（101–130 lbs）、3 = 60–70 kg（131–160 lbs）、4 = 71–86 kg（161–190 lbs）、5 = 87–100 kg（191–220 lbs）、6 = 101–113 kg（221–250 lbs）、7 = 114–127 kg（251–280 lbs）、8 = 128–145 kg（281–320 lbs）、9 = 146 kg以上（321 lbs以上）、DL/ID、F1N |

### 関連項目

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



---
title: "クラス USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields クラス。カードの必須要素フィールド"
type: docs
weight: 820
url: /ja/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

カードの必須要素（フィールド）

```csharp
public class MandatoryFields
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI、カード所有者住所の市区町村部分、DL/ID、V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK、米国およびカナダにおけるカード所有者住所の郵便番号部分。米国の郵便番号の末尾が不明な場合、0 が使用され、最大 9 桁になるまで数字が埋められます。DL/ID、F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ、カード所有者住所の州部分、DL/ID、F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG、カード所有者住所の通り部分、DL/ID、V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG、DL/ID が発行される国。米国 = USA、カナダ = CAN、DL/ID、F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ、発行機関が割り当てまたは計算した番号、DL/ID、V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB、文書が発行された日付、米国は MMDDCCYY、カナダは CCYYMMDD、DL/ID、F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF、番号はその顧客に発行された特定の文書を過去に発行された他の文書と区別できるように一意である必要があります。この番号は文書の識別、監査情報番号、または在庫管理など複数の目的に使用される場合があります、DL/ID、V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD、管轄区域固有の裏書コード、DL、V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA、文書有効期限、米国はMMDDCCYY、カナダはCCYYMMDD、DL/ID、F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY、カード所有者の目の色。（ANSI D-20コード）。DL/ID、F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS、カード所有者の姓、DL/ID、V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE、フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC、カード所有者の名、DL/ID、V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF、フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU、カード所有者の身長。インチ（in）：数値の後に「 in」を付ける 例：6'1'' = "073 in" センチメートル（cm）：数値の後に「 cm」を付ける 例：181センチメートル = "181 cm"、DL/ID、F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD、文書が発行された日付、米国はMMDDCCYY、カナダはCCYYMMDD、DL/ID、F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD、カード所有者のミドルネーム。複数のミドルネームがある場合はカンマ「,」で区切ります。、DL/ID、V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG、フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB、管轄区域固有の制限コード、DL、V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC、カード所有者の性別。1=男性、2=女性、9=未指定、DL/ID、F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA、管轄区域固有の車両クラス/グループコード、DL、V6ANS |

### 関連項目

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



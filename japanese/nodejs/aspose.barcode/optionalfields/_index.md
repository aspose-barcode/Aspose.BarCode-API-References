---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "カードのオプション要素（フィールド）"
type: docs
weight: 730
url: /ja/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

カードのオプション要素（フィールド）

```js
new OptionalFields()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN、カード所有者が知られているその他の姓、DL/ID、V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG、カード所有者が知られているその他の名、DL/ID、V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS、カード所有者が知られているその他の接尾辞、DL/ID、V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ、運転免許証/ID カードがいつ、どこで、誰によって作成されたかを識別する文字列（文字と/または数字）。もし a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, DHS が必要とするフィールドで、最新のバージョン変更または可視形式の修正日を示します |
| [getComplianceType()](#getcompliancetype) | DDA, DHS が必要とするフィールドで、コンプライアンスを示します: “F” = 準拠; “N” = 非準拠, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, 管轄固有のコードが追加の運転特権を示すことを説明するテキスト |
| [getHairColor()](#gethaircolor) | DAZ, 禿頭、黒、ブロンド、茶色、灰色、赤/オーバーン、サンド、白、未知. 発行管轄が省略したい場合は |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, 文書によって付与された危険物エンドースメントが無効になる日付. (米国は MMDDCCYY、 |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, 原材料（カードストック、ラミネート等）に貼付される文字列（英字および/または数字） |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, DHS が必要とするフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, 名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS 等）に参加している場合、サフィックスは必須です） |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, カード所有者が臓器提供者であることを示すフィールド = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, 国および自治体、または州/県, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, カード所有者の人種または民族を示すコード（AAMVA D20で定義）, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, 運転特権を制限する管轄固有の制限コードを説明するテキスト, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, カード所有者用の標準エンドースメントコード. D20 のコードを参照してください. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, カード所有者用の標準制限コード. D20 のコードを参照してください. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, カード所有者用の標準車両分類コード. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [getUnder18Until()](#getunder18until) | DDH, カード所有者が18歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, カード所有者が21歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, カード所有者が運転許可された車両分類に関する管轄固有コードを説明するテキスト |
| [getVeteranIndicator()](#getveteranindicator) | DDL, カード所有者がベテランであることを示すフィールド = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, カード所有者の体重（キログラム）、例: 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, カード所有者の体重（ポンド）、例: 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, カード所有者の概算体重範囲を示す: 0 = 31 kg まで（70 lbs まで）、1 = 32 – 45 kg（71 – 100 lbs） |
| [setAddressStreet2()](#setaddressstreet2) | DAH, カード所有者住所の通り部分の第2行, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN、カード所有者が知られているその他の姓、DL/ID、V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG、カード所有者が知られているその他の名、DL/ID、V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS、カード所有者が知られているその他の接尾辞、DL/ID、V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ、運転免許証/ID カードがいつ、どこで、誰によって作成されたかを識別する文字列（文字と/または数字）。もし a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, DHS が必要とするフィールドで、最新のバージョン変更または可視形式の修正日を示します |
| [setComplianceType()](#setcompliancetype) | DDA, DHS が必要とするフィールドで、コンプライアンスを示します: “F” = 準拠; “N” = 非準拠, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, 管轄固有のコードが追加の運転特権を示すことを説明するテキスト |
| [setHairColor()](#sethaircolor) | DAZ, 禿頭、黒、ブロンド、茶色、灰色、赤/オーバーン、サンド、白、未知. 発行管轄が省略したい場合は |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, 原材料（カードストック、ラミネート等）に貼付される文字列（英字および/または数字） |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, DHS が必要とするフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, 名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS 等）に参加している場合、サフィックスは必須です） |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, カード所有者が臓器提供者であることを示すフィールド = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, 国および自治体、または州/県, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, カード所有者の人種または民族を示すコード（AAMVA D20で定義）, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, 運転特権を制限する管轄固有の制限コードを説明するテキスト, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, カード所有者用の標準エンドースメントコード. D20 のコードを参照してください. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, カード所有者用の標準制限コード. D20 のコードを参照してください. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, カード所有者用の標準車両分類コード. このデータ要素は将来の取り組みのためのプレースホルダーです |
| [setUnder18Until()](#setunder18until) | DDI, カード所有者が19歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, カード所有者が19歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, カード所有者が21歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, カード所有者が運転許可された車両分類に関する管轄固有コードを説明するテキスト |
| [setVeteranIndicator()](#setveteranindicator) | DDL, カード所有者がベテランであることを示すフィールド = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, カード所有者の体重（キログラム）、例: 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, カード所有者の体重（ポンド）、例: 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, カード所有者の概算体重範囲を示す: 0 = 31 kg まで（70 lbs まで）、1 = 32 – 45 kg（71 – 100 lbs） |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN、カード所有者が知られているその他の姓、DL/ID、V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG、カード所有者が知られているその他の名、DL/ID、V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS、カード所有者が知られているその他の接尾辞、DL/ID、V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（英字および/または数字）。カードまたは MRT に監査情報が使用されていない場合は、運転者記録に含める必要があります, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB、DHS が必須とするフィールドで、DL/ID の表示形式の最新バージョン変更または修正の日付を示します。（米国は MMDDCCYY、カナダは CCYYMMDD）、DL/ID、F8N

### getComplianceType() {#getcompliancetype}

DDA, DHS が必要とするフィールドで、コンプライアンスを示します: “F” = 準拠; “N” = 非準拠, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ、管轄区域固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト、DL、V50ANS

### getHairColor() {#gethaircolor}

DAZ、禿頭、黒、ブロンド、茶色、灰色、赤/赤褐色、砂色、白、不明。発行管轄が色を省略したい場合は、AAMVA D20 で提供される3文字コードを使用しなければなりません、DL/ID、V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC、文書によって付与された危険物エンドースメントが無効になる日付。（米国は MMDDCCYY、カナダは CCYYMMDD）、DL、F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK、運転免許証や ID カードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列または数字の組み合わせ。（DHS 推奨フィールド）、DL/ID、V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, DHS が必要とするフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU、名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS など）に参加している場合、サフィックスは DL/ID および MRT に収集・表示されなければなりません）。JR（Junior）、SR（Senior）、1ST または I（First）、9TH または IX（Ninth）まで、DL/ID、V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, カード所有者が臓器提供者であることを示すフィールド = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, 国および自治体、または州/県, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, カード所有者の人種または民族を示すコード（AAMVA D20で定義）, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, 運転特権を制限する管轄固有の制限コードを説明するテキスト, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN、カード所有者の標準エンドースメントコード。D20 のコードを参照してください。このデータ要素は、エンドースメントコードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO、カード所有者の標準制限コード。D20 のコードを参照してください。このデータ要素は、制限コードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM、カード所有者の標準車両分類コード。このデータ要素は、車両分類の標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F4AN

### getUnder18Until() {#getunder18until}

DDH, カード所有者が18歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, カード所有者が21歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP、カード所有者が運転許可を受けている車両の分類に関する管轄固有コードを説明するテキスト、DL、V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, カード所有者がベテランであることを示すフィールド = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, カード所有者の体重（キログラム）、例: 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, カード所有者の体重（ポンド）、例: 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE、カード所有者の概算体重範囲を示します：0 = 31 kg 以下（70 ポンド以下）、1 = 32 – 45 kg（71 – 100 ポンド）、2 = 46 - 59 kg（101 – 130 ポンド）、3 = 60 - 70 kg（131 – 160 ポンド）、4 = 71 - 86 kg（161 – 190 ポンド）、5 = 87 - 100 kg（191 – 220 ポンド）、6 = 101 - 113 kg（221 – 250 ポンド）、7 = 114 - 127 kg（251 – 280 ポンド）、8 = 128 – 145 kg（281 – 320 ポンド）、9 = 146 kg 超（321 ポンド超）、DL/ID、F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, カード所有者住所の通り部分の第2行, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN、カード所有者が知られているその他の姓、DL/ID、V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG、カード所有者が知られているその他の名、DL/ID、V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS、カード所有者が知られているその他の接尾辞、DL/ID、V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（英字および/または数字）。カードまたは MRT に監査情報が使用されていない場合は、運転者記録に含める必要があります, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB、DHS が必須とするフィールドで、DL/ID の表示形式の最新バージョン変更または修正の日付を示します。（米国は MMDDCCYY、カナダは CCYYMMDD）、DL/ID、F8N

### setComplianceType() {#setcompliancetype}

DDA, DHS が必要とするフィールドで、コンプライアンスを示します: “F” = 準拠; “N” = 非準拠, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ、管轄区域固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト、DL、V50ANS

### setHairColor() {#sethaircolor}

DAZ、禿頭、黒、ブロンド、茶色、灰色、赤/赤褐色、砂色、白、不明。発行管轄が色を省略したい場合は、AAMVA D20 で提供される3文字コードを使用しなければなりません、DL/ID、V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK、運転免許証や ID カードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列または数字の組み合わせ。（DHS 推奨フィールド）、DL/ID、V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, DHS が必要とするフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU、名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS など）に参加している場合、サフィックスは DL/ID および MRT に収集・表示されなければなりません）。JR（Junior）、SR（Senior）、1ST または I（First）、9TH または IX（Ninth）まで、DL/ID、V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, カード所有者が臓器提供者であることを示すフィールド = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, 国および自治体、または州/県, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, カード所有者の人種または民族を示すコード（AAMVA D20で定義）, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, 運転特権を制限する管轄固有の制限コードを説明するテキスト, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN、カード所有者の標準エンドースメントコード。D20 のコードを参照してください。このデータ要素は、エンドースメントコードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO、カード所有者の標準制限コード。D20 のコードを参照してください。このデータ要素は、制限コードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM、カード所有者の標準車両分類コード。このデータ要素は、車両分類の標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F4AN

### setUnder18Until() {#setunder18until}

DDI, カード所有者が19歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, カード所有者が19歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, カード所有者が21歳になる日付. (米国は MMDDCCYY、カナダは CCYYMMDD), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP、カード所有者が運転許可を受けている車両の分類に関する管轄固有コードを説明するテキスト、DL、V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, カード所有者がベテランであることを示すフィールド = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, カード所有者の体重（キログラム）、例: 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, カード所有者の体重（ポンド）、例: 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE、カード所有者の概算体重範囲を示します：0 = 31 kg 以下（70 ポンド以下）、1 = 32 – 45 kg（71 – 100 ポンド）、2 = 46 - 59 kg（101 – 130 ポンド）、3 = 60 - 70 kg（131 – 160 ポンド）、4 = 71 - 86 kg（161 – 190 ポンド）、5 = 87 - 100 kg（191 – 220 ポンド）、6 = 101 - 113 kg（221 – 250 ポンド）、7 = 114 - 127 kg（251 – 280 ポンド）、8 = 128 – 145 kg（281 – 320 ポンド）、9 = 146 kg 超（321 ポンド超）、DL/ID、F1N

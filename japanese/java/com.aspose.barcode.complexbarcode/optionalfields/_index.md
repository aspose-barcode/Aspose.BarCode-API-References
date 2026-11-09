---
title: "USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "カードのオプション要素フィールド"
type: docs
weight: 11
url: /ja/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

カードのオプション要素（フィールド）
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH、カード所有者住所の通り部分の2行目、DL/ID、V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN、カード所有者が知られている他の姓、DL/ID、V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG、カード所有者が知られている他の名、DL/ID、V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS、カード所有者が知られている他の接尾辞、DL/ID、V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（文字または数字）。 |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, DHSが要求するフィールドで、DL/IDの可視形式の最新バージョン変更または修正の日付を示す。 |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, DHSが要求するフィールドで、コンプライアンスを示す: \u201cF\u201d = 準拠; そして, \u201cN\u201d = 非準拠, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, 管轄固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, 文書によって付与された危険物取扱許可が有効でなくなる日付。 |
| [getHairColor()](#getHairColor--) | DAZ, はげ, 黒, 金髪, 茶色, 灰色, 赤/赤褐色, 砂色, 白, 不明。 |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, 運転免許証およびIDカードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列（文字または数字）。 |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, DHSが要求するフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, 名前のサフィックス（管轄が名前サフィックスを要求するシステム（PDPS、CDLIS等）に参加している場合、サフィックスはDL/IDおよびMRTに収集・表示されなければならない）。 |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, カード所有者が臓器提供者であることを示すフィールド = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, 国および自治体、または州/県, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, AAMVA D20で定義されたカード所有者の人種または民族のコード, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, 運転特権を制限する管轄固有の制限コードを記述するテキスト, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, カード所有者の標準エンドースメントコード。 |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, カード所有者の標準制限コード。 |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, カード所有者の標準車両分類コード。 |
| [getUnder18Until()](#getUnder18Until--) | DDH, カード所有者が18歳になる日付。 |
| [getUnder19Until()](#getUnder19Until--) | DDI, カード所有者が19歳になる日付。 |
| [getUnder21Until()](#getUnder21Until--) | DDJ, カード所有者が21歳になる日付。 |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, カード所有者が運転許可された車両の分類に関する管轄固有のコードを説明するテキスト, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, カード所有者がベテランであることを示すフィールド = \u201c1\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, カード所有者の体重（キログラム）、例。 |
| [getWeightPounds()](#getWeightPounds--) | DAW, カード所有者の体重（ポンド）、例。 |
| [getWeightRange()](#getWeightRange--) | DCE, カード所有者の概算体重範囲を示す: 0 = 31 kgまで（70 lbsまで）、1 = 32 \u2013 45 kg（71 \u2013 100 lbs）、2 = 46 - 59 kg（101 \u2013 130 lbs）、3 = 60 - 70 kg（131 \u2013 160 lbs）、4 = 71 - 86 kg（161 \u2013 190 lbs）、5 = 87 - 100 kg（191 \u2013 220 lbs）、6 = 101 - 113 kg（221 \u2013 250 lbs）、7 = 114 - 127 kg（251 \u2013 280 lbs）、8 = 128 \u2013 145 kg（281 \u2013 320 lbs）、9 = 146+ kg（321+ lbs）、 DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH、カード所有者住所の通り部分の2行目、DL/ID、V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN、カード所有者が知られている他の姓、DL/ID、V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG、カード所有者が知られている他の名、DL/ID、V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS、カード所有者が知られている他の接尾辞、DL/ID、V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（文字または数字）。 |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, DHSが要求するフィールドで、DL/IDの可視形式の最新バージョン変更または修正の日付を示す。 |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, DHSが要求するフィールドで、コンプライアンスを示す: \u201cF\u201d = 準拠; そして, \u201cN\u201d = 非準拠, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, 管轄固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト, DL, V50ANS |
| [setHAZMATEndorsementExpDate(LocalDate value)](#setHAZMATEndorsementExpDate-java.time.LocalDate-) | DDC, 文書によって付与された危険物取扱許可が有効でなくなる日付。 |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, はげ, 黒, 金髪, 茶色, 灰色, 赤/赤褐色, 砂色, 白, 不明。 |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, 運転免許証およびIDカードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列（文字または数字）。 |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, DHSが要求するフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, 名前のサフィックス（管轄が名前サフィックスを要求するシステム（PDPS、CDLIS等）に参加している場合、サフィックスはDL/IDおよびMRTに収集・表示されなければならない）。 |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, カード所有者が臓器提供者であることを示すフィールド = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, 国および自治体、または州/県, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, AAMVA D20で定義されたカード所有者の人種または民族のコード, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, 運転特権を制限する管轄固有の制限コードを記述するテキスト, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, カード所有者の標準エンドースメントコード。 |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, カード所有者の標準制限コード。 |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, カード所有者の標準車両分類コード。 |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, カード所有者が18歳になる日付。 |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, カード所有者が19歳になる日付。 |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, カード所有者が21歳になる日付。 |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, カード所有者が運転許可された車両の分類に関する管轄固有のコードを説明するテキスト, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, カード所有者がベテランであることを示すフィールド = \u201c1\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, カード所有者の体重（キログラム）、例。 |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, カード所有者の体重（ポンド）、例。 |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, カード所有者の概算体重範囲を示す: 0 = 31 kgまで（70 lbsまで）、1 = 32 \u2013 45 kg（71 \u2013 100 lbs）、2 = 46 - 59 kg（101 \u2013 130 lbs）、3 = 60 - 70 kg（131 \u2013 160 lbs）、4 = 71 - 86 kg（161 \u2013 190 lbs）、5 = 87 - 100 kg（191 \u2013 220 lbs）、6 = 101 - 113 kg（221 \u2013 250 lbs）、7 = 114 - 127 kg（251 \u2013 280 lbs）、8 = 128 \u2013 145 kg（281 \u2013 320 lbs）、9 = 146+ kg（321+ lbs）、 DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH、カード所有者住所の通り部分の2行目、DL/ID、V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN、カード所有者が知られている他の姓、DL/ID、V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG、カード所有者が知られている他の名、DL/ID、V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS、カード所有者が知られている他の接尾辞、DL/ID、V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（文字または数字）。カードまたはMRTで監査情報が使用されていない場合、運転者記録に含める必要があります, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB、DHSが必須とするフィールドで、DL/IDの可視形式の最新バージョン変更または修正の日付を示します。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, DHSが要求するフィールドで、コンプライアンスを示す: \u201cF\u201d = 準拠; そして, \u201cN\u201d = 非準拠, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, 管轄固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC、文書によって付与された危険物エンドースメントの有効期限が切れる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL、F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ、禿頭、黒、金髪、茶色、灰色、赤/赤褐色、砂色、白、不明。発行管轄が色を省略したい場合は、AAMVA D20で提供される3文字コードを使用する必要があります、DL/ID、V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK、運転免許証やIDカードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列（英字および/または数字）。（DHS推奨フィールド）、DL/ID、V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, DHSが要求するフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU、名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS等）に参加している場合、サフィックスはDL/IDおよびMRTに収集・表示される必要があります）。JR（Junior）、SR（Senior）、1STまたはI（First）、9THまたはIX（Ninth）まで、DL/ID、V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, カード所有者が臓器提供者であることを示すフィールド = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, 国および自治体、または州/県, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, AAMVA D20で定義されたカード所有者の人種または民族のコード, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, 運転特権を制限する管轄固有の制限コードを記述するテキスト, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN、カード所有者の標準エンドースメントコード。コードはD20を参照してください。このデータ要素は、エンドースメントコードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO、カード所有者の標準制限コード。コードはD20を参照してください。このデータ要素は、制限コードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM、カード所有者の標準車両分類コード。このデータ要素は、車両分類の標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH、カード所有者が18歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI、カード所有者が19歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ、カード所有者が21歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, カード所有者が運転許可された車両の分類に関する管轄固有のコードを説明するテキスト, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, カード所有者がベテランであることを示すフィールド = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX、カード所有者の体重（キログラム）、例: 84 kg = \\u201c084\\u201d、DL/ID、F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW、カード所有者の体重（ポンド）、例: 185 lb = \\u201c185\\u201d、DL/ID、F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, カード所有者の概算体重範囲を示す: 0 = 31 kgまで（70 lbsまで）、1 = 32 \u2013 45 kg（71 \u2013 100 lbs）、2 = 46 - 59 kg（101 \u2013 130 lbs）、3 = 60 - 70 kg（131 \u2013 160 lbs）、4 = 71 - 86 kg（161 \u2013 190 lbs）、5 = 87 - 100 kg（191 \u2013 220 lbs）、6 = 101 - 113 kg（221 \u2013 250 lbs）、7 = 114 - 127 kg（251 \u2013 280 lbs）、8 = 128 \u2013 145 kg（281 \u2013 320 lbs）、9 = 146+ kg（321+ lbs）、 DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH、カード所有者住所の通り部分の2行目、DL/ID、V35ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN、カード所有者が知られている他の姓、DL/ID、V10ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG、カード所有者が知られている他の名、DL/ID、V15ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS、カード所有者が知られている他の接尾辞、DL/ID、V5ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, 運転免許証/IDカードがいつ、どこで、誰によって作成されたかを識別する文字列（文字または数字）。カードまたはMRTで監査情報が使用されていない場合、運転者記録に含める必要があります, DL/ID, V25ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB、DHSが必須とするフィールドで、DL/IDの可視形式の最新バージョン変更または修正の日付を示します。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, DHSが要求するフィールドで、コンプライアンスを示す: \u201cF\u201d = 準拠; そして, \u201cN\u201d = 非準拠, DL/ID, F1A

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, 管轄固有のコードが、車両クラスを超えてカード所有者に付与された追加の運転特権を示すことを説明するテキスト, DL, V50ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setHAZMATEndorsementExpDate(LocalDate value) {#setHAZMATEndorsementExpDate-java.time.LocalDate-}
```
public final void setHAZMATEndorsementExpDate(LocalDate value)
```


DDC、文書によって付与された危険物エンドースメントの有効期限が切れる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL、F8N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ、禿頭、黒、金髪、茶色、灰色、赤/赤褐色、砂色、白、不明。発行管轄が色を省略したい場合は、AAMVA D20で提供される3文字コードを使用する必要があります、DL/ID、V12A

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK、運転免許証やIDカードの製造に使用される原材料（カードストック、ラミネート等）に貼付される文字列（英字および/または数字）。（DHS推奨フィールド）、DL/ID、V25ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, DHSが要求するフィールドで、カード所有者が一時的な合法ステータスを持つことを示す = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU、名前のサフィックス（管轄が名前サフィックスを必要とするシステム（PDPS、CDLIS等）に参加している場合、サフィックスはDL/IDおよびMRTに収集・表示される必要があります）。JR（Junior）、SR（Senior）、1STまたはI（First）、9THまたはIX（Ninth）まで、DL/ID、V5ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, カード所有者が臓器提供者であることを示すフィールド = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, 国および自治体、または州/県, DL/ID, V33A

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, AAMVA D20で定義されたカード所有者の人種または民族のコード, DL/ID, V3A

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, 運転特権を制限する管轄固有の制限コードを記述するテキスト, DL, V50ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN、カード所有者の標準エンドースメントコード。コードはD20を参照してください。このデータ要素は、エンドースメントコードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F5AN

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO、カード所有者の標準制限コード。コードはD20を参照してください。このデータ要素は、制限コードの標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F12AN

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM、カード所有者の標準車両分類コード。このデータ要素は、車両分類の標準化に向けた将来の取り組みのためのプレースホルダーです、DL、F4AN

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH、カード所有者が18歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI、カード所有者が19歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ、カード所有者が21歳になる日付。（米国はMMDDCCYY、カナダはCCYYMMDD）、DL/ID、F8N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, カード所有者が運転許可された車両の分類に関する管轄固有のコードを説明するテキスト, DL, V50ANS

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, カード所有者がベテランであることを示すフィールド = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX、カード所有者の体重（キログラム）、例: 84 kg = \\u201c084\\u201d、DL/ID、F3N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW、カード所有者の体重（ポンド）、例: 185 lb = \\u201c185\\u201d、DL/ID、F3N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, カード所有者の概算体重範囲を示す: 0 = 31 kgまで（70 lbsまで）、1 = 32 \u2013 45 kg（71 \u2013 100 lbs）、2 = 46 - 59 kg（101 \u2013 130 lbs）、3 = 60 - 70 kg（131 \u2013 160 lbs）、4 = 71 - 86 kg（161 \u2013 190 lbs）、5 = 87 - 100 kg（191 \u2013 220 lbs）、6 = 101 - 113 kg（221 \u2013 250 lbs）、7 = 114 - 127 kg（251 \u2013 280 lbs）、8 = 128 \u2013 145 kg（281 \u2013 320 lbs）、9 = 146+ kg（321+ lbs）、 DL/ID, F1N

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


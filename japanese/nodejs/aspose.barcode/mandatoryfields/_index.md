---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "カードの必須要素（フィールド）"
type: docs
weight: 590
url: /ja/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

カードの必須要素（フィールド）

```js
new MandatoryFields()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, City portion of the cardholder address, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK、米国およびカナダのカード所有者住所の郵便番号部分。郵便番号の末尾部分が |
| [getAddressState()](#getaddressstate) | DAJ、カード所有者住所の州部分、DL/ID、F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG、カード所有者住所の通り部分、DL/ID、V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, DL/ID が発行される国。米国 = USA、カナダ = CAN、DL/ID、F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, 発行機関が割り当てまたは計算した番号、DL/ID、V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, 書類が発行された日付、米国は MMDDCCYY、カナダは CCYYMMDD、DL/ID、F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, 番号はその顧客に発行された特定の書類を他の発行済み書類と区別できるように一意である必要があります i |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, 管轄固有のエンドースメントコード、DL、V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, カード所有者の目の色。（ANSI D-20 コード）。DL/ID、F3A |
| [getFamilyName()](#getfamilyname) | DCS, カード所有者の姓、DL/ID、V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [getFirstName()](#getfirstname) | DAC, カード所有者の名、DL/ID、V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [getHeight()](#getheight) | DAU, カード所有者の身長。インチ（in）：数値の後に " in" を付ける 例: 6'1'' = "073 in" センチメートル（cm）：数値の後に " cm" を付ける |
| [getMiddleName()](#getmiddlename) | DAD, カード所有者のミドルネーム。複数のミドルネームがある場合はカンマ "," で区切ります。 , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, 管轄固有の制限コード、DL、V12ANS |
| [getSex()](#getsex) | DBC, カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, 管轄固有の車両クラス/グループコード、DL、V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, City portion of the cardholder address, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK、米国およびカナダのカード所有者住所の郵便番号部分。郵便番号の末尾部分が |
| [setAddressState()](#setaddressstate) | DAJ、カード所有者住所の州部分、DL/ID、F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG、カード所有者住所の通り部分、DL/ID、V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, DL/ID が発行される国。米国 = USA、カナダ = CAN、DL/ID、F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, 発行機関が割り当てまたは計算した番号、DL/ID、V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, 書類が発行された日付、米国は MMDDCCYY、カナダは CCYYMMDD、DL/ID、F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, 番号はその顧客に発行された特定の書類を他の発行済み書類と区別できるように一意である必要があります i |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, 管轄固有のエンドースメントコード、DL、V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, カード所有者の目の色。（ANSI D-20 コード）。DL/ID、F3A |
| [setFamilyName()](#setfamilyname) | DCS, カード所有者の姓、DL/ID、V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [setFirstName()](#setfirstname) | DAC, カード所有者の名、DL/ID、V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [setHeight()](#setheight) | DAU, カード所有者の身長。インチ（in）：数値の後に " in" を付ける 例: 6'1'' = "073 in" センチメートル（cm）：数値の後に " cm" を付ける |
| [setMiddleName()](#setmiddlename) | DAD, カード所有者のミドルネーム。複数のミドルネームがある場合はカンマ "," で区切ります。 , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、または不明） |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, 管轄固有の制限コード、DL、V12ANS |
| [setSex()](#setsex) | DBC, カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, 管轄固有の車両クラス/グループコード、DL、V6ANS |

### getAddressCity() {#getaddresscity}

DAI, City portion of the cardholder address, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, 米国およびカナダのカード所有者住所の郵便番号部分。米国で郵便番号の末尾が不明な場合、0で埋めて最大9桁にします、DL/ID、F11ANS

### getAddressState() {#getaddressstate}

DAJ、カード所有者住所の州部分、DL/ID、F2A

### getAddressStreet1() {#getaddressstreet1}

DAG、カード所有者住所の通り部分、DL/ID、V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, DL/ID が発行される国。米国 = USA、カナダ = CAN、DL/ID、F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, 発行機関が割り当てまたは計算した番号、DL/ID、V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, 書類が発行された日付、米国は MMDDCCYY、カナダは CCYYMMDD、DL/ID、F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, 番号は過去に発行された他の書類と区別できるように、その顧客に発行された特定の書類を一意に識別する必要があります。この番号は書類の識別、監査情報番号、在庫管理など複数の目的に使用される場合があります、DL/ID、V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, 管轄固有のエンドースメントコード、DL、V5ANS

### getEyeColor() {#geteyecolor}

DAY, カード所有者の目の色。（ANSI D-20 コード）。DL/ID、F3A

### getFamilyName() {#getfamilyname}

DCS, カード所有者の姓、DL/ID、V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### getFirstName() {#getfirstname}

DAC, カード所有者の名、DL/ID、V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### getHeight() {#getheight}

DAU, カード所有者の身長。インチ（in）：数値の後に " in" を付ける 例: 6'1'' = "073 in" センチメートル（cm）：数値の後に " cm" を付ける 例: 181センチメートル = "181 cm" , DL/ID、F6ANS

### getMiddleName() {#getmiddlename}

DAD, カード所有者のミドルネーム。�数のミドルネームがある場合はカンマ "," で区切ります。 , DL/ID、V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, 管轄固有の制限コード、DL、V12ANS

### getSex() {#getsex}

DBC, カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N

### getVehicleClass() {#getvehicleclass}

DCA, 管轄固有の車両クラス/グループコード、DL、V6ANS

### setAddressCity() {#setaddresscity}

DAI, City portion of the cardholder address, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, 米国およびカナダのカード所有者住所の郵便番号部分。米国で郵便番号の末尾が不明な場合、0で埋めて最大9桁にします、DL/ID、F11ANS

### setAddressState() {#setaddressstate}

DAJ、カード所有者住所の州部分、DL/ID、F2A

### setAddressStreet1() {#setaddressstreet1}

DAG、カード所有者住所の通り部分、DL/ID、V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, DL/ID が発行される国。米国 = USA、カナダ = CAN、DL/ID、F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, 発行機関が割り当てまたは計算した番号、DL/ID、V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, 書類が発行された日付、米国は MMDDCCYY、カナダは CCYYMMDD、DL/ID、F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, 番号は過去に発行された他の書類と区別できるように、その顧客に発行された特定の書類を一意に識別する必要があります。この番号は書類の識別、監査情報番号、在庫管理など複数の目的に使用される場合があります、DL/ID、V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, 管轄固有のエンドースメントコード、DL、V5ANS

### setEyeColor() {#seteyecolor}

DAY, カード所有者の目の色。（ANSI D-20 コード）。DL/ID、F3A

### setFamilyName() {#setfamilyname}

DCS, カード所有者の姓、DL/ID、V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### setFirstName() {#setfirstname}

DAC, カード所有者の名、DL/ID、V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### setHeight() {#setheight}

DAU, カード所有者の身長。インチ（in）：数値の後に " in" を付ける 例: 6'1'' = "073 in" センチメートル（cm）：数値の後に " cm" を付ける 例: 181センチメートル = "181 cm" , DL/ID、F6ANS

### setMiddleName() {#setmiddlename}

DAD, カード所有者のミドルネーム。�数のミドルネームがある場合はカンマ "," で区切ります。 , DL/ID、V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, フィールドが切り詰められたかどうかを示すコード（T=切り詰め、N=未切り詰め、U=不明）、DL/ID、F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, 管轄固有の制限コード、DL、V12ANS

### setSex() {#setsex}

DBC, カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N

### setVehicleClass() {#setvehicleclass}

DCA, 管轄固有の車両クラス/グループコード、DL、V6ANS

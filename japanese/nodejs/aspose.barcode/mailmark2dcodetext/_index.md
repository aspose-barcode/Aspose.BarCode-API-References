---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 570
url: /ja/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark コードに埋め込まれたテキストをエンコードおよびデコードするクラス。

```js
new Mailmark2DCodetext()
```

Mailmark2DCodetext クラスのデフォルトインスタンスを作成します。

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | バーコードのタイプを取得します。 |
| [getClass_()](#getclass-) | アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - Economy（小売） '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark データからコードテキストを構築します。 |
| [getCustomerContent()](#getcustomercontent) | 顧客が使用するための任意のスペースです。タイプ別の最大長: Type 7: 6 文字、Type 9: 45 文字、Type 29: 25 文字 |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Datamatrix バーコードのエンコードモードです。デフォルト値: DataMatrixEncodeMode.C40。 |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark Type は Data Matrix バーコードのサイズを定義します。 |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | 配送先住所の郵便番号（DPS 付き）を含みます。内陸の場合、Postcode/DP は以下の文字数を含みます |
| [getInformationTypeID()](#getinformationtypeid) | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。有効な値: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは ID を保持する必要があり、... |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Return to Sender の郵便番号を含みますが、DPS は含みません。DPS なしの PC は PAF® 形式に準拠する必要があります。 |
| [getRTSFlag()](#getrtsflag) | 要求されている Return to Sender サービスのレベルを示すフラグです。 |
| [getSupplyChainID()](#getsupplychainid) | メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。 |
| [getUPUCountryID()](#getupucountryid) | UPU 国コードを識別します。最大長さ: 4 文字。 |
| [getVersionID()](#getversionid) | 各情報タイプ ID に関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2' から '9' まで an |
| [initFromString(constructedCodetext)](#initfromstring) | 構築されたコードテキストから Mailmark データを初期化します。 |
| [setClass_(value)](#setclass-) | アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - Economy（小売） '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | 顧客が使用するための任意のスペースです。タイプ別の最大長: Type 7: 6 文字、Type 9: 45 文字、Type 29: 25 文字 |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Datamatrix バーコードのエンコードモードです。デフォルト値: DataMatrixEncodeMode.C40。 |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark Type は Data Matrix バーコードのサイズを定義します。 |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | 配送先住所の郵便番号（DPS 付き）を含みます。内陸の場合、Postcode/DP は以下の文字数を含みます |
| [setInformationTypeID(value)](#setinformationtypeid) | 各製品タイプに対する Royal Mail Mailmark バーコードのペイロードを識別します。有効な値: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは ID を保持する必要があり、... |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Return to Sender の郵便番号を含みますが、DPS は含みません。DPS なしの PC は PAF® 形式に準拠する必要があります。 |
| [setRTSFlag()](#setrtsflag) | 要求されている Return to Sender サービスのレベルを示すフラグです。 |
| [setSupplyChainID(value)](#setsupplychainid) | メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。 |
| [setUPUCountryID(value)](#setupucountryid) | UPU 国コードを識別します。最大長さ: 4 文字。 |
| [setVersionID(value)](#setversionid) | 各情報タイプ ID に関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2' から '9' まで an |

### getBarcodeType() {#getbarcodetype}

バーコードのタイプを取得します。

**Returns:** Barcode type.

### getClass_() {#getclass-}

アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - エコノミー（小売） '5' - Deffered（小売） '8' - プレミアム（ネットワークアクセス） '9' - スタンダード（ネットワークアクセス）

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark データからコードテキストを構築します。

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

顧客が使用するための任意のスペースです。タイプ別の最大長さ: タイプ 7: 6 文字 タイプ 9: 45 文字 タイプ 29: 25 文字

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Datamatrix バーコードのエンコードモードです。デフォルト値: DataMatrixEncodeMode.C40。

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark Type は Data Matrix バーコードのサイズを定義します。

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

配達先住所の郵便番号と DPS を含みます。内陸の場合、郵便番号/DP は以下の文字数を含みます。エリア (1 または 2 文字) 区 (1 または 2 文字) セクター (1 文字) ユニット (2 文字) DPS (2 文字)。郵便番号と DPS は有効な PAF® フォーマットに準拠している必要があります。

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

各製品タイプに対するロイヤルメール Mailmark バーコードペイロードを識別します。有効な値: '0' - 国内ソート済み・未ソート 'A' - オンライン郵便 'B' - フランキング 'C' - コンソリデーション

**Returns:** Information type ID

### getItemID() {#getitemid}

サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは ID を保持する必要があり、少なくとも 90 日間ユニークに識別できます。最大値: 99999999。

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Return to Sender の郵便番号を含みますが、DPS は含みません。DPS なしの PC は PAF® 形式に準拠する必要があります。

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

要求されている Return to Sender サービスのレベルを示すフラグです。

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

UPU 国コードを識別します。最大長さ: 4 文字。

**Returns:** Country ID

### getVersionID() {#getversionid}

各情報タイプ ID に関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2' から '9'、および 'A' から 'Z' は将来の使用のために予備として予約されています。

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

構築されたコードテキストから Mailmark データを初期化します。

| パラメータ | 説明 |
| --- | --- |
| constructedCodetext | 構築された codetext。 |

### setClass_(value) {#setclass-}

アイテムのクラスを識別します。有効な値: '1' - 1C（小売） '2' - 2C（小売） '3' - エコノミー（小売） '5' - Deffered（小売） '8' - プレミアム（ネットワークアクセス） '9' - スタンダード（ネットワークアクセス）

| パラメータ | 説明 |
| --- | --- |
| 値 | アイテムのクラス |

### setCustomerContent(value) {#setcustomercontent}

顧客が使用するための任意のスペースです。タイプ別の最大長さ: タイプ 7: 6 文字 タイプ 9: 45 文字 タイプ 29: 25 文字

| パラメータ | 説明 |
| --- | --- |
| 値 | 顧客コンテンツ |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Datamatrix バーコードのエンコードモードです。デフォルト値: DataMatrixEncodeMode.C40。

| パラメータ | 説明 |
| --- | --- |
| 値 | DataMatrix バーコードのエンコードモード。 |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark Type は Data Matrix バーコードのサイズを定義します。

| パラメータ | 説明 |
| --- | --- |
| 値 | Data Matrix バーコードのサイズ |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

配達先住所の郵便番号と DPS を含みます。内陸の場合、郵便番号/DP は以下の文字数を含みます。エリア (1 または 2 文字) 区 (1 または 2 文字) セクター (1 文字) ユニット (2 文字) DPS (2 文字)。郵便番号と DPS は有効な PAF® フォーマットに準拠している必要があります。

| パラメータ | 説明 |
| --- | --- |
| 値 | 配達先住所の郵便番号と DPS |

### setInformationTypeID(value) {#setinformationtypeid}

各製品タイプに対するロイヤルメール Mailmark バーコードペイロードを識別します。有効な値: '0' - 国内ソート済み・未ソート 'A' - オンライン郵便 'B' - フランキング 'C' - コンソリデーション

| パラメータ | 説明 |
| --- | --- |
| 値 | 情報タイプ ID |

### setItemID(value) {#setitemid}

サプライチェーン ID 内のユニークなアイテムを識別します。すべての Mailmark バーコードは ID を保持する必要があり、少なくとも 90 日間ユニークに識別できます。最大値: 99999999。

| パラメータ | 説明 |
| --- | --- |
| 値 | サプライチェーン ID 内のアイテム |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Return to Sender の郵便番号を含みますが、DPS は含みません。DPS なしの PC は PAF® 形式に準拠する必要があります。

| パラメータ | 説明 |
| --- | --- |
| 値 | 差出人返送用郵便番号（DPS なし） |

### setRTSFlag() {#setrtsflag}

要求されている Return to Sender サービスのレベルを示すフラグです。

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

メールに関与する顧客のユニークなグループを識別します。最大値: 9999999。

| パラメータ | 説明 |
| --- | --- |
| 値 | サプライチェーン ID |

### setUPUCountryID(value) {#setupucountryid}

UPU 国コードを識別します。最大長さ: 4 文字。

| パラメータ | 説明 |
| --- | --- |
| 値 | 国 ID |

### setVersionID(value) {#setversionid}

各情報タイプ ID に関連するバーコードバージョンを識別します。有効な値: 現在は '1'。'0' と '2' から '9'、および 'A' から 'Z' は将来の使用のために予備として予約されています。

| パラメータ | 説明 |
| --- | --- |
| 値 | バージョン ID |

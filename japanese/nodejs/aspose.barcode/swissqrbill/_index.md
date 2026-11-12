---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "SwissQR 請求書データ"
type: docs
weight: 920
url: /ja/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR 請求書データ

```js
new SwissQRBill()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | 生の文字列に "RF" をプレフィックスし、モジュロ97チェックを行うことで ISO11649 の債権者参照を作成し設定します。 |
| [equals(obj)](#equals) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getAccount()](#getaccount) | 債権者の口座番号を取得します。口座番号はスイスまたはリヒテンシュタインの銀行の有効な IBAN である必要があります。Space |
| [getAlternativeSchemes()](#getalternativeschemes) | 代替支払スキームを取得または設定します。パラメータ付きスキームは最大で2つまで許可されます。 |
| [getAmount()](#getamount) | 支払金額を取得します。有効な値は0.01から999,999,999.99までです。 |
| [getBillInformation()](#getbillinformation) | 追加の構造化請求書情報を取得します。 |
| [getCreditor()](#getcreditor) | 債権者の住所を取得します。 |
| [getCurrency()](#getcurrency) | 支払通貨を取得します。有効な値は "CHF" と "EUR" です。 |
| [getDebtor()](#getdebtor) | 債務者の住所を取得します。債務者は任意です。省略した場合、このフィールドを null に設定するか、住所を設定することで対応できます。 |
| [getReference()](#getreference) | 債権者の支払参照を取得します。SwissQR IBAN では参照が必須です。例: CHxx30000xxxxx の範囲の IBAN。 |
| [getUnstructuredMessage()](#getunstructuredmessage) | 追加の非構造化メッセージを取得します。 |
| [getVersion()](#getversion) | SwissQR請求書標準のバージョンを取得します。 |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを取得します。 |
| [setAccount(value:)](#setaccount) | 債権者の口座番号を設定します。口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。スペース |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | 代替支払スキームを取得または設定します。パラメータ付きスキームは最大2つまで許可されます。 |
| [setAmount(value)](#setamount) | 支払金額を設定します。有効な値は0.01から999,999,999.99までです。 |
| [setBillInformation(value:)](#setbillinformation) | 追加の構造化請求情報を設定します。 |
| [setCreditor(value:)](#setcreditor) | 債権者の住所を設定します。 |
| [setCurrency(value)](#setcurrency) | 支払通貨を設定します。 |
| [setDebtor(value:)](#setdebtor) | 債務者の住所を設定します。債務者はオプションです。省略した場合、このフィールドをnullに設定するか、住所を設定するかのいずれかが可能です。 |
| [setReference(value)](#setreference) | 債権者の支払参照を設定します。参照はSwissQR IBAN（例：CHxx30000xxxxx の範囲）に対して必須です。 |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | 追加の非構造化メッセージを設定します。 |
| [setVersion(value)](#setversion) | SwissQR請求書標準のバージョンを設定します。 |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

生文字列に "RF" を前置し、モジュロ97チェックサムを付加して ISO11649 債権者参照を作成し設定します。参照から空白は除去されます。

| パラメータ | 説明 |
| --- | --- |
| rawReference | 生の参照です。 |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| obj | 現在のオブジェクトと比較するオブジェクトです。 |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

債権者の口座番号を取得します。口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。口座番号内のスペースは許可されます。

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

代替支払スキームを取得または設定します。パラメータ付きスキームは最大で2つまで許可されます。

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

支払金額を取得します。有効な値は0.01から999,999,999.99までです。

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

追加の構造化請求書情報を取得します。

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

債権者の住所を取得します。

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

支払通貨を取得します。有効な値は "CHF" と "EUR" です。

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

債務者の住所を取得します。債務者はオプションです。省略した場合、このフィールドをnullに設定するか、すべての値がnullまたは空の住所を設定するかのいずれでも構いません。

**Returns:** The debtor address.

### getReference() {#getreference}

債権者の支払参照を取得します。参照はSwissQR IBAN（例：CHxx30000xxxxxx から CHxx31999xxxxx の範囲）に対して必須です。指定された場合、参照は有効なSwissQR参照（ISR参照形式に対応）またはISO 11649（"RFxxxx"）に基づく有効な債権者参照のいずれかでなければなりません。どちらも書式設定のためにスペースを含むことができます。

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

追加の非構造化メッセージを取得します。

**Returns:** The unstructured message.

### getVersion() {#getversion}

SwissQR請求書標準のバージョンを取得します。

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

このインスタンスのハッシュコードを取得します。

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

債権者の口座番号を設定します。口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。口座番号内のスペースは許可されます。

| パラメータ | 説明 |
| --- | --- |
| 値: | 債権者の口座番号です。 |

### setAlternativeSchemes(value:) {#setalternativeschemes}

代替支払スキームを取得または設定します。パラメータ付きスキームは最大2つまで許可されます。

| パラメータ | 説明 |
| --- | --- |
| 値: | 代替支払スキームです。 |

### setAmount(value) {#setamount}

支払金額を設定します。有効な値は0.01から999,999,999.99までです。

| パラメータ | 説明 |
| --- | --- |
| 値 | 支払金額です。 |

### setBillInformation(value:) {#setbillinformation}

追加の構造化請求情報を設定します。

| パラメータ | 説明 |
| --- | --- |
| 値: | 構造化請求情報です。 |

### setCreditor(value:) {#setcreditor}

債権者の住所を設定します。

| パラメータ | 説明 |
| --- | --- |
| 値: | 債権者の住所です。 |

### setCurrency(value) {#setcurrency}

支払通貨を設定します。

| パラメータ | 説明 |
| --- | --- |
| 値 | 有効な値は "CHF" と "EUR" です。 |

### setDebtor(value:) {#setdebtor}

債務者の住所を設定します。債務者はオプションです。省略した場合、このフィールドをnullに設定するか、すべての値がnullまたは空の住所を設定するかのいずれでも構いません。

| パラメータ | 説明 |
| --- | --- |
| 値: | 債務者の住所。 |

### setReference(value) {#setreference}

債権者の支払参照を設定します。スイスQR IBAN（例：CHxx30000xxxxxx から CHxx31999xxxxx の範囲）の場合、この参照は必須です。指定された場合、参照は有効なスイスQR参照（ISR 参照形式に対応）または ISO 11649（\"RFxxxx\"）に準拠した有効な債権者参照のいずれかでなければなりません。どちらも書式設定のためにスペースを含めることができます。

| パラメータ | 説明 |
| --- | --- |
| 値 | 債権者の支払参照。 |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

追加の非構造化メッセージを設定します。

| パラメータ | 説明 |
| --- | --- |
| 値: | 構造化されていないメッセージ。 |

### setVersion(value) {#setversion}

SwissQR請求書標準のバージョンを設定します。

| パラメータ | 説明 |
| --- | --- |
| 値 | スイスQR請求書標準バージョン。 |

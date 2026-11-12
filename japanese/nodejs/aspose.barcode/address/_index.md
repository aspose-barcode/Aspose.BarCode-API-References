---
title: "住所"
linktitle: "住所"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "債権者または債務者の住所。"
type: docs
weight: 10
url: /ja/nodejs/aspose.barcode/address/
---

## Address class

債権者または債務者の住所。ストリート、番地、郵便番号、町（構造化住所タイプ）を設定するか、アドレスライン 1 と 2（結合住所要素タイプ）を設定するかのいずれかが可能です。いずれかのフィールドが設定されると、タイプは自動的に設定されます。フィールドを設定する前は、住所タイプは未定義です。両方のタイプのフィールドが設定されると、住所タイプは競合状態になります。すべてのフィールドが空でない限り、名前と国コードは常に設定する必要があります。

```js
new Address()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [clear()](#clear) | すべてのフィールドをクリアし、タイプを AddressType.UNDETERMINED に設定します。 |
| [equals(obj)](#equals) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getAddressLine1()](#getaddressline1) | アドレスライン 1 を取得します。アドレスライン 1 には通り名、番地または私書箱が含まれます。このフィールドを設定すると、addr が設定されます |
| [getAddressLine2()](#getaddressline2) | アドレスライン 2 を取得します。アドレスライン 2 には郵便番号と町が含まれます。このフィールドを設定すると、住所タイプが Addre に設定されます |
| [getCountryCode()](#getcountrycode) | 2 文字の ISO 国コードを取得します。住所全体が null または空の値でない限り、国コードは必須です |
| [getHouseNo()](#gethouseno) | 番地を取得します。このフィールドを設定すると、住所タイプが AddressType.STRUCTURED に設定されます（既に AddressTyp でない限り） |
| [getName()](#getname) | 名前を取得します。自然人の場合は姓と名、法人の場合は会社名が対象です。 |
| [getPostalCode()](#getpostalcode) | 郵便番号を取得します。このフィールドを設定すると、住所タイプが AddressType.STRUCTURED に設定されます（既に AddressType でない限り） |
| [getStreet()](#getstreet) | 通り名を取得します。通り名は番地なしで指定する必要があります。このフィールドを設定すると、住所タイプが AddressT に設定されます |
| [getTown()](#gettown) | 町または市を取得します。このフィールドを設定すると、住所タイプが AddressType.STRUCTURED に設定されます（既に AddressTyp でない限り） |
| [getType()](#gettype) | 住所タイプを取得します。住所タイプは、通り／番地を設定するか、アドレスライン 1 を設定することで自動的に設定されます a |
| [hashCode()](#hashcode) | このインスタンスのハッシュコードを取得します。 |
| [setAddressLine1(value:)](#setaddressline1) | アドレスライン 1 を設定します。アドレスライン 1 には通り名、番地または私書箱が含まれます。このフィールドを設定すると、addr が設定されます |
| [setAddressLine2(value:)](#setaddressline2) | アドレスライン2を設定します。アドレスライン2には郵便番号と町が含まれます。このフィールドを設定すると、アドレスタイプが Addre に設定されます。 |
| [setCountryCode(value)](#setcountrycode) | 2文字の ISO 国コードを設定します。住所全体が null または空の値を含む場合を除き、国コードは必須です。 |
| [setHouseNo(value:)](#sethouseno) | 住宅番号を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressTyp である場合は除きます。 |
| [setName(value:)](#setname) | 名前を設定します。自然人の姓と名、または法人の会社名のいずれかです。 |
| [setPostalCode(value)](#setpostalcode) | 郵便番号を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType である場合は除きます。 |
| [setStreet(value:)](#setstreet) | 通りを設定します。通りは住宅番号なしで指定する必要があります。このフィールドを設定すると、アドレスタイプが AddressT に設定されます。 |
| [setTown(value)](#settown) | 町または市を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressTyp である場合は除きます。 |

### clear() {#clear}

すべてのフィールドをクリアし、タイプを AddressType.UNDETERMINED に設定します。

### equals(obj) {#equals}

指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

| パラメータ | 説明 |
| --- | --- |
| obj | 現在のオブジェクトと比較するオブジェクトです。 |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

アドレスライン1を取得します。アドレスライン1には通り名、住宅番号または私書箱が含まれます。このフィールドを設定すると、アドレスタイプが AddressType.COMBINED_ELEMENTS に設定されます。ただし、すでに AddressType.STRUCTURED である場合は、AddressType.CONFLICTING になります。このフィールドは結合要素アドレスでのみ使用され、オプションです。

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

アドレスライン2を取得します。アドレスライン2には郵便番号と町が含まれます。このフィールドを設定すると、アドレスタイプが AddressType.COMBINED_ELEMENTS に設定されます。ただし、すでに AddressType.STRUCTURED である場合は、AddressType.CONFLICTING になります。このフィールドは結合要素アドレスでのみ使用されます。このタイプでは必須です。

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

2文字の ISO 国コードを取得します。住所全体が null または空の値を含む場合を除き、国コードは必須です。

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

住宅番号を取得します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType.COMBINED_ELEMENTS である場合は、AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用され、オプションです。

**Returns:** The house number.

### getName() {#getname}

名前を取得します。自然人の場合は姓と名、法人の場合は会社名が対象です。

**Returns:** The name.

### getPostalCode() {#getpostalcode}

郵便番号を取得します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType.COMBINED_ELEMENTS である場合は、AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

**Returns:** The postal code.

### getStreet() {#getstreet}

通りを取得します。通りは住宅番号なしで指定する必要があります。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType.COMBINED_ELEMENTS である場合は、AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用され、オプションです。

**Returns:** The street.

### getTown() {#gettown}

町または市を取得します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType.COMBINED_ELEMENTS である場合は、AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

**Returns:** The town or city.

### getType() {#gettype}

アドレスタイプを取得します。アドレスタイプは、通り/住宅番号を設定するか、アドレスライン1と2を設定することで自動的に設定されます。フィールドを設定する前は、アドレスタイプは Undetermined です。両方のタイプのフィールドが設定されると、アドレスタイプは Conflicting になります。

**Returns:** The address type.

### hashCode() {#hashcode}

このインスタンスのハッシュコードを取得します。

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

アドレスライン1を設定します。アドレスライン1には通り名、住宅番号または私書箱が含まれます。このフィールドを設定すると、アドレスタイプが AddressType.COMBINED_ELEMENTS に設定されます。ただし、すでに AddressType.STRUCTURED である場合は、AddressType.CONFLICTING になります。このフィールドは結合要素アドレスでのみ使用され、オプションです。

| パラメータ | 説明 |
| --- | --- |
| 値: | アドレスライン1。 |

### setAddressLine2(value:) {#setaddressline2}

アドレスライン2を設定します。アドレスライン2には郵便番号と町が含まれます。このフィールドを設定すると、アドレスタイプが AddressType.COMBINED_ELEMENTS に設定されます。ただし、すでに AddressType.STRUCTURED である場合は、AddressType.CONFLICTING になります。このフィールドは結合要素アドレスでのみ使用されます。このタイプでは必須です。

| パラメータ | 説明 |
| --- | --- |
| 値: | アドレスライン2。 |

### setCountryCode(value) {#setcountrycode}

2文字の ISO 国コードを設定します。住所全体が null または空の値を含む場合を除き、国コードは必須です。

| パラメータ | 説明 |
| --- | --- |
| 値 | ISO 国コード。 |

### setHouseNo(value:) {#sethouseno}

住宅番号を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されます。ただし、すでに AddressType.COMBINED_ELEMENTS である場合は、AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用され、オプションです。

| パラメータ | 説明 |
| --- | --- |
| 値: | 住宅番号。 |

### setName(value:) {#setname}

名前を設定します。自然人の姓と名、または法人の会社名のいずれかです。

| パラメータ | 説明 |
| --- | --- |
| 値: | 名前。 |

### setPostalCode(value) {#setpostalcode}

郵便番号を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されますが、すでに AddressType.COMBINED_ELEMENTS の場合は AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

| パラメータ | 説明 |
| --- | --- |
| 値 | 郵便番号。 |

### setStreet(value:) {#setstreet}

通りを設定します。通りは番地なしで指定する必要があります。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されますが、すでに AddressType.COMBINED_ELEMENTS の場合は AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用され、オプションです。

| パラメータ | 説明 |
| --- | --- |
| 値: | 通り。 |

### setTown(value) {#settown}

町または市を設定します。このフィールドを設定すると、アドレスタイプが AddressType.STRUCTURED に設定されますが、すでに AddressType.COMBINED_ELEMENTS の場合は AddressType.CONFLICTING になります。このフィールドは構造化アドレスでのみ使用されます。このタイプでは必須です。

| パラメータ | 説明 |
| --- | --- |
| 値 | 町または市。 |

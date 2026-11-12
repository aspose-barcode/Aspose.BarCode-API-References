---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "SwissQR 账单数据"
type: docs
weight: 920
url: /zh/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR 账单数据

```js
new SwissQRBill()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | 创建并设置 ISO11649 债权人参考号，从原始字符串通过在字符串前添加 "RF" 并进行 modulo 97 校验 |
| [equals(obj)](#equals) | 确定指定的对象是否等于当前对象。 |
| [getAccount()](#getaccount) | 获取债权人的账户号码。账户号码必须是瑞士或列支敦士登银行的有效 IBAN。Space |
| [getAlternativeSchemes()](#getalternativeschemes) | 获取或设置替代付款方案。最多允许两个带参数的方案。 |
| [getAmount()](#getamount) | 获取付款金额。有效值在 0.01 到 999,999,999.99 之间。 |
| [getBillInformation()](#getbillinformation) | 获取附加的结构化账单信息。 |
| [getCreditor()](#getcreditor) | 获取债权人地址。 |
| [getCurrency()](#getcurrency) | 获取付款货币。有效值为 "CHF" 和 "EUR"。 |
| [getDebtor()](#getdebtor) | 获取债务人地址。债务人是可选的。如果省略，可将此字段设为 null 或设置地址 |
| [getReference()](#getreference) | 获取债权人付款参考。对于 SwissQR IBAN（即范围为 CHxx30000xxxxx 的 IBAN），此参考是必需的。 |
| [getUnstructuredMessage()](#getunstructuredmessage) | 获取附加的非结构化消息。 |
| [getVersion()](#getversion) | 获取 SwissQR 账单标准的版本。 |
| [hashCode()](#hashcode) | 获取此实例的哈希码。 |
| [setAccount(value:)](#setaccount) | 设置债权人的账户号码。账户号码必须是瑞士或列支敦士登银行的有效 IBAN。空格 |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | 获取或设置替代付款方案。最多允许两个带参数的方案。 |
| [setAmount(value)](#setamount) | 设置付款金额。有效值范围为 0.01 到 999,999,999.99。 |
| [setBillInformation(value:)](#setbillinformation) | 设置附加的结构化账单信息。 |
| [setCreditor(value:)](#setcreditor) | 设置债权人地址。 |
| [setCurrency(value)](#setcurrency) | 设置付款货币。 |
| [setDebtor(value:)](#setdebtor) | 设置债务人地址。债务人是可选的。如果省略，则可以将此字段设为 null，或设置一个地址 |
| [setReference(value)](#setreference) | 设置债权人付款参考。对于 SwissQR IBAN（即范围在 CHxx30000xxxxx 的 IBAN），此参考是必需的。 |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | 设置附加的非结构化消息。 |
| [setVersion(value)](#setversion) | 设置 SwissQR 账单标准的版本。 |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

通过在原始字符串前加上 \"RF\" 并计算模 97 校验和，创建并设置 ISO11649 债权人参考。参考中的空白字符会被移除。

| 参数 | 描述 |
| --- | --- |
| rawReference | 原始参考。 |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

确定指定的对象是否等于当前对象。

| 参数 | 描述 |
| --- | --- |
| obj | 与当前对象比较的对象。 |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

获取债权人的账户号码。账户号码必须是瑞士或列支敦士登银行的有效 IBAN。账户号码中允许出现空格。

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

获取或设置替代付款方案。最多允许两个带参数的方案。

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

获取付款金额。有效值在 0.01 到 999,999,999.99 之间。

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

获取附加的结构化账单信息。

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

获取债权人地址。

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

获取付款货币。有效值为 "CHF" 和 "EUR"。

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

获取债务人地址。债务人是可选的。如果省略，则可以将此字段设为 null，或设置一个所有值均为 null 或空的地址。

**Returns:** The debtor address.

### getReference() {#getreference}

获取债权人付款参考。对于 SwissQR IBAN（即范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 的 IBAN），此参考是必需的。如果指定，参考必须是有效的 SwissQR 参考（对应 ISR 参考表格）或符合 ISO 11649 的有效债权人参考（\"RFxxxx\"）。两者均可包含空格用于格式化。

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

获取附加的非结构化消息。

**Returns:** The unstructured message.

### getVersion() {#getversion}

获取 SwissQR 账单标准的版本。

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

获取此实例的哈希码。

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

设置债权人的账户号码。账户号码必须是瑞士或列支敦士登银行的有效 IBAN。账户号码中允许出现空格。

| 参数 | 描述 |
| --- | --- |
| 值： | 债权人账户号码。 |

### setAlternativeSchemes(value:) {#setalternativeschemes}

获取或设置替代付款方案。最多允许两个带参数的方案。

| 参数 | 描述 |
| --- | --- |
| 值： | 替代付款方案。 |

### setAmount(value) {#setamount}

设置付款金额。有效值范围为 0.01 到 999,999,999.99。

| 参数 | 描述 |
| --- | --- |
| 值 | 付款金额。 |

### setBillInformation(value:) {#setbillinformation}

设置附加的结构化账单信息。

| 参数 | 描述 |
| --- | --- |
| 值： | 结构化账单信息。 |

### setCreditor(value:) {#setcreditor}

设置债权人地址。

| 参数 | 描述 |
| --- | --- |
| 值： | 债权人地址。 |

### setCurrency(value) {#setcurrency}

设置付款货币。

| 参数 | 描述 |
| --- | --- |
| 值 | 有效值为 \"CHF\" 和 \"EUR\"。 |

### setDebtor(value:) {#setdebtor}

设置债务人地址。债务人是可选的。如果省略，则可以将此字段设为 null，或设置一个所有值均为 null 或空的地址。

| 参数 | 描述 |
| --- | --- |
| 值： | 债务人地址。 |

### setReference(value) {#setreference}

设置债权人付款参考。该参考在 SwissQR IBAN 中是必需的，例如范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 之间的 IBAN。如果指定，参考必须是有效的 SwissQR 参考（对应 ISR 参考表格）或符合 ISO 11649（"RFxxxx"）的有效债权人参考。两者都可以包含用于格式化的空格。

| 参数 | 描述 |
| --- | --- |
| 值 | 债权人付款参考。 |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

设置附加的非结构化消息。

| 参数 | 描述 |
| --- | --- |
| 值： | 非结构化消息。 |

### setVersion(value) {#setversion}

设置 SwissQR 账单标准的版本。

| 参数 | 描述 |
| --- | --- |
| 值 | SwissQR 账单标准版本。 |

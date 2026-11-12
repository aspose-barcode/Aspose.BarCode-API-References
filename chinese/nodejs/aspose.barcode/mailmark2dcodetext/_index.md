---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。"
type: docs
weight: 570
url: /zh/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

用于对嵌入 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。

```js
new Mailmark2DCodetext()
```

创建 Mailmark2DCodetext 类的默认实例。

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 获取条形码类型。 |
| [getClass_()](#getclass-) | 标识项目的类别。有效值：'1' - 1C（零售）'2' - 2C（零售）'3' - 经济型（零售）'5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | 从 Mailmark 数据构建代码文本。 |
| [getCustomerContent()](#getcustomercontent) | 供客户使用的可选空间。按类型的最大长度：类型 7：6 个字符，类型 9：45 个字符，类型 29：25 个字符。 |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.C40。 |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark 类型定义 Data Matrix 条形码的尺寸。 |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | 包含带有 DPS 的收货地址邮政编码。如果是内陆，邮政编码/DP 包含以下字符数 |
| [getInformationTypeID()](#getinformationtypeid) | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。有效值：'0' - 国内已分拣和未分拣 |
| [getItemID()](#getitemid) | 标识供应链 ID 中的唯一项目。每个 Mailmark 条形码都必须携带一个 ID，以便能够未 |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | 包含退回寄件人邮编，但没有 DPS。没有 DPS 的 PC 必须符合 PAF® 格式。 |
| [getRTSFlag()](#getrtsflag) | 指示请求的退回寄件人服务级别的标志。 |
| [getSupplyChainID()](#getsupplychainid) | 标识参与邮件的唯一客户组。最大值：9999999。 |
| [getUPUCountryID()](#getupucountryid) | 标识UPU国家ID。最大长度：4个字符。 |
| [getVersionID()](#getversionid) | 标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'和'2'至'9'以及 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构建的代码文本初始化 Mailmark 数据。 |
| [setClass_(value)](#setclass-) | 标识项目的类别。有效值：'1' - 1C（零售）'2' - 2C（零售）'3' - 经济型（零售）'5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | 供客户使用的可选空间。按类型的最大长度：类型 7：6 个字符，类型 9：45 个字符，类型 29：25 个字符。 |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.C40。 |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark 类型定义 Data Matrix 条形码的尺寸。 |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | 包含带有 DPS 的收货地址邮政编码。如果是内陆，邮政编码/DP 包含以下字符数 |
| [setInformationTypeID(value)](#setinformationtypeid) | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。有效值：'0' - 国内已分拣和未分拣 |
| [setItemID(value)](#setitemid) | 标识供应链 ID 中的唯一项目。每个 Mailmark 条形码都必须携带一个 ID，以便能够未 |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | 包含退回寄件人邮编，但没有 DPS。没有 DPS 的 PC 必须符合 PAF® 格式。 |
| [setRTSFlag()](#setrtsflag) | 指示请求的退回寄件人服务级别的标志。 |
| [setSupplyChainID(value)](#setsupplychainid) | 标识参与邮件的唯一客户组。最大值：9999999。 |
| [setUPUCountryID(value)](#setupucountryid) | 标识UPU国家ID。最大长度：4个字符。 |
| [setVersionID(value)](#setversionid) | 标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'和'2'至'9'以及 |

### getBarcodeType() {#getbarcodetype}

获取条形码类型。

**Returns:** Barcode type.

### getClass_() {#getclass-}

标识项目的类别。有效值：'1' - 1C（零售） '2' - 2C（零售） '3' - 经济（零售） '5' - 延期（零售） '8' - 高级（网络访问） '9' - 标准（网络访问）

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

从 Mailmark 数据构建代码文本。

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

供客户使用的可选空间。按类型的最大长度：类型7：6个字符，类型9：45个字符，类型29：25个字符。

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.C40。

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark 类型定义 Data Matrix 条形码的尺寸。

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

包含带有DPS的收货地址邮编。如果是内陆，邮编/DP包含以下字符数。地区（1或2个字符） 区（1或2个字符） 扇区（1个字符） 单元（2个字符） DPS（2个字符）。邮编和DPS必须符合有效的PAF®格式。

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

标识皇家邮政Mailmark条码在每种产品类型中的负载。有效值：'0' - 国内已分类和未分类 'A' - 在线邮资 'B' - 贴票 'C' - 合并

**Returns:** Information type ID

### getItemID() {#getitemid}

标识供应链ID内的唯一项目。每个Mailmark条码必须携带一个ID，以便在至少90天内唯一识别。最大值：99999999。

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

包含退回寄件人邮编，但没有 DPS。没有 DPS 的 PC 必须符合 PAF® 格式。

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

指示请求的退回寄件人服务级别的标志。

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

标识参与邮件的唯一客户组。最大值：9999999。

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

标识UPU国家ID。最大长度：4个字符。

**Returns:** Country ID

### getVersionID() {#getversionid}

标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'和'2'至'9'以及'A'至'Z'保留供未来潜在使用。

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

从构建的代码文本初始化 Mailmark 数据。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setClass_(value) {#setclass-}

标识项目的类别。有效值：'1' - 1C（零售） '2' - 2C（零售） '3' - 经济（零售） '5' - 延期（零售） '8' - 高级（网络访问） '9' - 标准（网络访问）

| 参数 | 描述 |
| --- | --- |
| 值 | 项目的类别 |

### setCustomerContent(value) {#setcustomercontent}

供客户使用的可选空间。按类型的最大长度：类型7：6个字符，类型9：45个字符，类型29：25个字符。

| 参数 | 描述 |
| --- | --- |
| 值 | 客户内容 |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Datamatrix 条形码的编码模式。默认值：DataMatrixEncodeMode.C40。

| 参数 | 描述 |
| --- | --- |
| 值 | Datamatrix条码的编码模式。 |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark 类型定义 Data Matrix 条形码的尺寸。

| 参数 | 描述 |
| --- | --- |
| 值 | Data Matrix条码的尺寸 |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

包含带有DPS的收货地址邮编。如果是内陆，邮编/DP包含以下字符数。地区（1或2个字符） 区（1或2个字符） 扇区（1个字符） 单元（2个字符） DPS（2个字符）。邮编和DPS必须符合有效的PAF®格式。

| 参数 | 描述 |
| --- | --- |
| 值 | 带有DPS的收货地址邮编 |

### setInformationTypeID(value) {#setinformationtypeid}

标识皇家邮政Mailmark条码在每种产品类型中的负载。有效值：'0' - 国内已分类和未分类 'A' - 在线邮资 'B' - 贴票 'C' - 合并

| 参数 | 描述 |
| --- | --- |
| 值 | 信息类型ID |

### setItemID(value) {#setitemid}

标识供应链ID内的唯一项目。每个Mailmark条码必须携带一个ID，以便在至少90天内唯一识别。最大值：99999999。

| 参数 | 描述 |
| --- | --- |
| 值 | 供应链ID内的项目 |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

包含退回寄件人邮编，但没有 DPS。没有 DPS 的 PC 必须符合 PAF® 格式。

| 参数 | 描述 |
| --- | --- |
| 值 | 退回寄件人邮编（无DPS） |

### setRTSFlag() {#setrtsflag}

指示请求的退回寄件人服务级别的标志。

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

标识参与邮件的唯一客户组。最大值：9999999。

| 参数 | 描述 |
| --- | --- |
| 值 | 供应链ID |

### setUPUCountryID(value) {#setupucountryid}

标识UPU国家ID。最大长度：4个字符。

| 参数 | 描述 |
| --- | --- |
| 值 | 国家ID |

### setVersionID(value) {#setversionid}

标识与每个信息类型ID相关的条码版本。有效值：当前为'1'。'0'和'2'至'9'以及'A'至'Z'保留供未来潜在使用。

| 参数 | 描述 |
| --- | --- |
| 值 | 版本ID |

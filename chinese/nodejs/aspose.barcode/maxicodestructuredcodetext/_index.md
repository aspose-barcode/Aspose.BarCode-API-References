---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对模式 2 和 3 的 MaxiCode 代码中嵌入的文本进行编码和解码的基类。"
type: docs
weight: 700
url: /zh/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

用于对模式 2 和 3 的 MaxiCode 代码中嵌入的文本进行编码和解码的基类。

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的值。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [getCountryCode()](#getcountrycode) | 标识 3 位国家代码。 |
| [getHashCode()](#gethashcode) | 返回此实例的哈希码。 |
| [getPostalCode()](#getpostalcode) | 标识邮政编码。模式 2 必须为 9 位数字，模式 3 必须为 6 个字母数字符号。 |
| [getSecondMessage()](#getsecondmessage) | 标识条形码的第二条信息。 |
| [getServiceCategory()](#getservicecategory) | 标识 3 位服务类别。 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setCountryCode()](#setcountrycode) | 标识 3 位国家代码。 |
| [setPostalCode()](#setpostalcode) | 标识邮政编码。模式 2 必须为 9 位数字，模式 3 必须为 6 个字母数字符号。 |
| [setSecondMessage()](#setsecondmessage) | 标识条形码的第二条信息。 |
| [setServiceCategory()](#setservicecategory) | 标识 3 位服务类别。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的值。

| 参数 | 描述 |
| --- | --- |
| obj | 一个用于与此实例比较的值 |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

标识 3 位国家代码。

### getHashCode() {#gethashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

标识邮政编码。模式 2 必须为 9 位数字，模式 3 必须为 6 个字母数字符号。

### getSecondMessage() {#getsecondmessage}

标识条形码的第二条信息。

### getServiceCategory() {#getservicecategory}

标识 3 位服务类别。

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setCountryCode() {#setcountrycode}

标识 3 位国家代码。

### setPostalCode() {#setpostalcode}

标识邮政编码。模式 2 必须为 9 位数字，模式 3 必须为 6 个字母数字符号。

### setSecondMessage() {#setsecondmessage}

标识条形码的第二条信息。

### setServiceCategory() {#setservicecategory}

标识 3 位服务类别。

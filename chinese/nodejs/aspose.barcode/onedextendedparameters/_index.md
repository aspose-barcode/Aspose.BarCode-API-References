---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别 1D 条形码的特殊数据，如独立的编码文本和校验和"
type: docs
weight: 720
url: /zh/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

存储已识别 1D 条形码的特殊数据，如独立的编码文本和校验和

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 OneDExtendedParameters 值。 |
| [getCheckSum()](#getchecksum) | 获取 1D 条码的校验和。值：1D 条码的校验和。 |
| [getValue()](#getvalue) | 获取没有校验和的 1D 条码的编码文本。值：没有校验和的 1D 条码的编码文本。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isEmpty()](#isempty) | 测试所有参数是否仅具有默认值。值：如果所有参数仅具有默认值则返回 `true`；否则返回 `false`。 |
| [toString()](#tostring) | 返回此 OneDExtendedParameters 的可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 OneDExtendedParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

获取 1D 条码的校验和。值：1D 条码的校验和。

### getValue() {#getvalue}

获取没有校验和的 1D 条码的编码文本。值：没有校验和的 1D 条码的编码文本。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

测试所有参数是否仅具有默认值。值：如果所有参数仅具有默认值则返回 `true`；否则返回 `false`。

### toString() {#tostring}

返回此 OneDExtendedParameters 的可读字符串表示。

**Returns:** A string that represents this OneDExtendedParameters.

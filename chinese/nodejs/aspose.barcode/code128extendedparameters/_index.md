---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别 Code128 条形码的特殊数据。表示已识别条形码的区域和条形码角度"
type: docs
weight: 240
url: /zh/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

存储已识别 Code128 条形码的特殊数据。表示已识别条形码的区域和条形码角度

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 Code128ExtendedParameters 值。 |
| [getCode128DataPortions()](#getcode128dataportions) | 获取已识别的 Code128 条形码的 Code128DataPortion 数组。Code128DataPortion 的值。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [toString()](#tostring) | 返回此 Code128ExtendedParameters 的可读字符串表示形式。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 Code128ExtendedParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

获取已识别的 Code128 条形码的 Code128DataPortion 数组。Code128DataPortion 的值。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

返回此 Code128ExtendedParameters 的可读字符串表示形式。

**Returns:** A string that represents this Code128ExtendedParameters.

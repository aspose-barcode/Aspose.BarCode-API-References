---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别条形码的 DataBar 附加信息"
type: docs
weight: 310
url: /zh/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

存储已识别条形码的 DataBar 附加信息

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 DataBarExtendedParameters 值。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [is2DCompositeComponent()](#is2dcompositecomponent) | 获取 DataBar 2D 复合组件标志。默认值为 false。 |
| [toString()](#tostring) | 返回此对象的可读字符串表示形式。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 DataBarExtendedParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 DataBarExtendedParameters 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

获取 DataBar 2D 复合组件标志。默认值为 false。

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

返回此对象的可读字符串表示形式。

**Returns:** A string that represents this .

---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "表示已识别条码的区域和条码角度"
type: docs
weight: 100
url: /zh/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

表示已识别条码的区域和条码角度

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 BarCodeRegionParameters 值。 |
| [getAngle()](#getangle) | 获取条形码的角度（0-360）。值：条形码的角度（0-360）。 |
| [getPoints()](#getpoints) | 获取条码区域的 Points 数组 值：返回条码区域的 Points 数组 |
| [getQuadrangle()](#getquadrangle) | 获取条码区域的 Quadrangle 值：返回条码区域的 Quadrangle |
| [getRectangle()](#getrectangle) | 获取条码区域的 Rectangle 值：返回条码区域的 Rectangle |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [toString()](#tostring) | 返回此 BarCodeRegionParameters 的可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 BarCodeRegionParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

获取条形码的角度（0-360）。值：条形码的角度（0-360）。

### getPoints() {#getpoints}

获取条码区域的 Points 数组 值：返回条码区域的 Points 数组

### getQuadrangle() {#getquadrangle}

获取条码区域的 Quadrangle 值：返回条码区域的 Quadrangle

### getRectangle() {#getrectangle}

获取条码区域的 Rectangle 值：返回条码区域的 Rectangle

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

返回此 BarCodeRegionParameters 的可读字符串表示。

**Returns:** A string that represents this BarCodeRegionParameters.

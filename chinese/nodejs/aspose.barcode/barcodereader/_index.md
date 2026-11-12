---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "BarCodeReader 封装可能包含一个或多个条形码的图像，然后可以执行 ReadBarCodes 操作来检测条形码。"
type: docs
weight: 90
url: /zh/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader 封装可能包含一个或多个条形码的图像，然后可以执行 ReadBarCodes 操作来检测条形码。

```js
new BarCodeReader(image, areas, decodeTypes)
```

初始化 BarCodeReader 的新实例

| 参数 | 描述 |
| --- | --- |
| 图像 | 以 base64 字符串或图像路径的形式编码 |
| 区域 | 按 Rectangle 类型的对象数组 |
| decodeTypes | 按 DecodeType 的对象数组 |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | 将 BarCode 属性导出到指定的 xml 文件 |
| [containsAny()](#containsany) | 确定给定的 decode types 是否包含在内 |
| [exportToXml(xmlFile)](#exporttoxml) | 将 BarCode 属性导出到指定的 xml 文件 |
| [getBarCodeReadType()](#getbarcodereadtype) | 获取输入条形码解码的 decode type |
| [getBarcodeSettings()](#getbarcodesettings) | 主要的 BarCode 解码参数。包含对识别数据产生影响的参数。 |
| [getFoundBarCodes()](#getfoundbarcodes) | 获取已识别的 BarCodeResult 数组 |
| [getFoundCount()](#getfoundcount) | 获取已识别的条形码数量 |
| [getQualitySettings()](#getqualitysettings) | QualitySettings 允许手动配置识别质量和速度。您可以通过 em 快速设置 QualitySettings |
| [getTimeout()](#gettimeout) | 获取识别过程的超时时间（毫秒）。 |
| [readBarCodes()](#readbarcodes) | 从图像读取 BarCodeResult。 |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | 设置位图图像和识别区域。必须在调用 ReadBarCodes() 方法之前调用此方法。 |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | 设置用于识别的 SingleDecodeType 类型数组。必须在调用 readBarCodes() 方法之前调用此方法。 |
| [setQualitySettings()](#setqualitysettings) | QualitySettings 允许手动配置识别质量和速度。您可以通过 em 快速设置 QualitySettings |
| [setTimeout(value)](#settimeout) | 设置识别过程的超时时间（毫秒）。 |

### importFromXml(xmlFile) (static) {#importfromxml}

将 BarCode 属性导出到指定的 xml 文件

| 参数 | 描述 |
| --- | --- |
| xmlFile | 文件的名称 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

确定给定的 decode types 是否包含在内

| 参数 | 描述 |
| --- | --- |
| ...decodeTypes | 要验证的 Types。 |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

将 BarCode 属性导出到指定的 xml 文件

| 参数 | 描述 |
| --- | --- |
| xmlFile | 文件的名称 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

获取输入条形码解码的 decode type

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

主要的 BarCode 解码参数。包含对识别数据产生影响的参数。

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

获取已识别的 BarCodeResult 数组

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

获取已识别的条形码数量

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或手动配置各个选项。QualitySettings 的默认值是 NormalQuality。

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

获取识别过程的超时时间（毫秒）。

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

从图像读取 BarCodeResult。

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

设置位图图像和识别区域。必须在调用 ReadBarCodes() 方法之前调用此方法。

| 参数 | 描述 |
| --- | --- |
| imageResource | 用于识别的图像。 |
| 区域 | 用于识别的 areas 列表 |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

设置用于识别的 SingleDecodeType 类型数组。必须在调用 readBarCodes() 方法之前调用此方法。

| 参数 | 描述 |
| --- | --- |
| types | 要读取的 SingleDecodeType 类型数组。 |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或手动配置各个选项。QualitySettings 的默认值是 NormalQuality。

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

设置识别过程的超时时间（毫秒）。

| 参数 | 描述 |
| --- | --- |
| 值 | 超时时间。 |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

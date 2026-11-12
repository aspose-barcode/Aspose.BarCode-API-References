---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别条形码的 MacroPdf417 元数据"
type: docs
weight: 760
url: /zh/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

存储已识别条形码的 MacroPdf417 元数据

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。 |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | 宏 PDF417 收件人名称（可选）。 |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | 宏 PDF417 校验和（可选）。 |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | 获取条码的文件 ID，仅在使用 MacroPdf417 时可用。值：MacroPdf417 的文件 ID。 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 文件名（可选）。 |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 文件大小（可选）。 |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | 获取条形码的段 ID，仅在 MacroPdf417 中可用。值：条形码的段 ID。 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | 获取 macro pdf417 条形码段计数。默认值为 -1。值：段计数。 |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 发送者名称（可选）。 |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 时间戳（可选）。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [isCode128Emulation()](#iscode128emulation) | 指示 MicroPdf417 条形码使用 908、909、910 或 911 Code 128 仿真码字编码的标志。 |
| [isLinked()](#islinked) | 指示条形码必须链接到 1D 条形码的标志。值：链接标志 |
| [isReaderInitialization()](#isreaderinitialization) | 用于指示读取器将符号中包含的数据解释为读取器初始化的编程。 |
| [toString()](#tostring) | 返回此 Pdf417ExtendedParameters 的人类可读字符串表示。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 Pdf417ExtendedParameters 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 System.Object 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

宏 PDF417 收件人名称（可选）。

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

宏 PDF417 校验和（可选）。

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

获取条码的文件 ID，仅在使用 MacroPdf417 时可用。值：MacroPdf417 的文件 ID。

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 文件名（可选）。

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 文件大小（可选）。

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

获取条形码的段 ID，仅在 MacroPdf417 中可用。值：条形码的段 ID。

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

获取 macro pdf417 条形码段计数。默认值为 -1。值：段计数。

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 发送者名称（可选）。

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 时间戳（可选）。

**Returns:** Time stamp.

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

指示 MicroPdf417 条形码使用 908、909、910 或 911 Code 128 仿真码字编码的标志。

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

指示条形码必须链接到 1D 条形码的标志。值：链接标志

### isReaderInitialization() {#isreaderinitialization}

用于指示读取器将符号中包含的数据解释为读取器初始化的编程。

**Returns:** Reader initialization flag

### toString() {#tostring}

返回此 Pdf417ExtendedParameters 的人类可读字符串表示。

**Returns:** A string that represents this Pdf417ExtendedParameters.

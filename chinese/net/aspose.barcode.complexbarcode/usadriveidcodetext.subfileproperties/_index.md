---
title: "类 USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextSubfileProperties 类。USA DL 子文件属性的偏移量和长度会自动设置"
type: docs
weight: 840
url: /zh/net/aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
## USADriveIdCodetext.SubfileProperties class

USA DL 子文件属性的偏移量和长度会自动设置。

```csharp
public class SubfileProperties
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Length](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/length) { get; set; } | 这 4 个字节包含一个 4 位数字值，指定子文件的字节长度。计算子文件长度时必须包括段终止符。段终止符 = 1。每个子文件必须以两个字符的子文件类型开头，这两个字符也必须计入长度。 |
| [Offset](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/offset) { get; set; } | 4 位数字值，指定从文件头部或开头到特定子文件相关数据所在位置的字节数。文件中的第一个字节位于偏移量 0。 |
| [Type](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/type) { get; set; } | 2 字节的子文件类型，例如 "DL" |

### 另见

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)



---
title: "DecodeType.Parse"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "DecodeType 方法。将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败"
type: docs
weight: 960
url: /zh/net/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType.Parse method

将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

```csharp
public static bool Parse(string parsingType, out SingleDecodeType result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parsingType | 字符串 | 包含 SingleDecodeType 的字符串，格式如 "EAN8"、"EAN13" 或 "CodaBar"... 用于转换。 |
| 结果 | SingleDecodeType& | 当转换成功完成时，实际返回 SingleDecodeType；否则返回不确定类型：DecodeType.None。 |

### 返回值

**true** if parsingType was converted successfully; otherwise, **false**.

### 另见

* class [SingleDecodeType](../../singledecodetype/)
* class [DecodeType](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


